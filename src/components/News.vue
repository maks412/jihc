<template>
  <div class="container">
    <h1 class="m-5 text-center" style="color: #0077ff">
      {{ $t("NewsH") }}
      <hr />
    </h1>
    <div class="row">
      <div
        class="col-12 col-md-4"
        v-for="item in localizedCards"
        :key="item.id"
      >
        <div class="card mb-3">
          <div class="image-container">
            <!-- Using v-bind to handle img src dynamically -->
            <img
              class="card-img-top"
              :src="item.imgPath"
              @error="handleImageError(item)"
              alt="News image"
            />
          </div>
          <div class="card-body">
            <h5 class="card-title fw-bold">{{ item.newsTitle }}</h5>
            <p
              class="card-text"
              :class="{ 'text-truncate': !item.isFullTextVisible }"
            >
              {{ item.description }}
            </p>
            <div class="my-auto d-flex justify-content-between">
              <button @click="toggleText(item.id)" class="btn btn-outline-primary">
                {{ item.isFullTextVisible ? $t("hide") : $t("readMore") }}
              </button>
              <p class="card-time my-auto text-muted">{{ item.createdAt }}</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import axios from "axios";

export default {
  data() {
    return {
      cards: [],
      text: "",
      SHEET_JSON_URL: `https://docs.google.com/spreadsheets/d/1yKWjPA9O5mOFMvL4D-GSd33azAnH0uMn-QKb686OTUY/gviz/tq?tqx=out:json`,
    };
  },
  computed: {
    currentLocale() {
      return this.$i18n.locale; // Get locale from vue-i18n
    },
    localizedCards() {
      return this.cards.map((item) => ({
        ...item,
        newsTitle: item.newsTitle[this.currentLocale] || item.newsTitle["ru"], // Default to Russian if missing
        description:
          item.description[this.currentLocale] || item.description["ru"], // Default to Russian if missing
      }));
    },
  },
  created() {
    this.fetchNews();
  },
  methods: {
    formatDate(value) {
      if (value) {
        const [day, month, year] = value.split(".");
        if (!day || !month || !year) return "Некорректная дата";
        return new Date(`${year}-${month}-${day}`).toLocaleDateString(
          this.currentLocale,
          {
            year: "numeric",
            month: "long",
            day: "numeric",
          }
        );
      }
      return "";
    },
    toggleText(id) {
      const card = this.cards.find((c) => c.id === id);
      if (card) card.isFullTextVisible = !card.isFullTextVisible;
    },
    handleImageError(item) {
      item.imgPath =
        "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQeJQeJyzgAzTEVqXiGe90RGBFhfp_4RcJJMQ&s"; // Placeholder image
    },
    async fetchNews() {
      try {
        const response = await axios.get(this.SHEET_JSON_URL);
        const jsonText = response.data.substring(47, response.data.length - 2);
        const jsonData = JSON.parse(jsonText);
        let rows = jsonData.table.rows;

        let parsedData = rows.map((row, index) => ({
          id: index + 1,
          newsTitle: {
            kz: row.c[0]?.v || "Тақырыбы жоқ",
            ru: row.c[1]?.v || "Без заголовка",
            en: row.c[2]?.v || "No title",
          },
          description: {
            kz: row.c[3]?.v || "Сипаттама жоқ",
            ru: row.c[4]?.v || "Нет описания",
            en: row.c[5]?.v || "No description",
          },
          createdAt: row.c[6]?.v || "",
          imgPath: row.c[7]?.v || "", // Google Drive Link
          isFullTextVisible: false, // Moved to cards array
        }));

        this.cards = parsedData.slice(1).reverse().slice(0, 3);
      } catch (error) {
        console.error("Error fetching news:", error);
      }
    },
  },
};
</script>

<style scoped>
.image-container {
  position: relative;
  width: 100%;
  height: 275px;
  display: flex;
  align-items: center;
  justify-content: center;
  background: #f3f3f3;
}

.card img {
  max-height: 275px;
  object-fit: cover;
  width: 100%;
}

.text-truncate {
  -webkit-line-clamp: 3;
  -webkit-box-orient: vertical;
  text-overflow: ellipsis;
}
</style>
