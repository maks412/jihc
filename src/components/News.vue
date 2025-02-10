<template>
  <div class="container">
    <div class="text-center">
      <h1 class="m-5 text-center" style="color: #0077ff">
        {{ text }}
        <hr />
      </h1>
    </div>
    <div class="row">
      <div class="col-12 col-md-4" v-for="item in cards" :key="item._id">
        <div class="card mb-3">
          <img class="card-img-top" :src="item.imgPath" alt="Card image cap" />
          <div class="card-body">
            <h5 class="card-title fw-bold">{{ item.newsTitle }}</h5>
            <p
              class="card-text"
              :class="{ 'text-truncate': !item.isFullTextVisible }"
            >
              {{ item.description }}
            </p>
            <button @click="toggleText(item)" class="btn btn-link p-0">
              {{ item.isFullTextVisible ? "Скрыть" : "Подробнее" }}
            </button>
            <p class="card-time">{{ formatDate(item.createdAt) }}</p>
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
    };
  },
  created() {
    this.fetchNews();
    this.fetchText();
  },
  methods: {
    formatDate(value) {
      if (value) {
        return new Date(value).toLocaleDateString("ru-RU", {
          year: "numeric",
          month: "long",
          day: "numeric",
          weekday: "long", // You can add this if you want to include the day of the week
        });
      }
      return "";
    },
    toggleText(card) {
      card.isFullTextVisible = !card.isFullTextVisible;
    },

    async fetchNews() {
      try {
        const response = await axios.get("https://jihc.edu.kz/api/news", {
          withCredentials: true,
        });

        // Sort the news items by date in descending order
        response.data.sort(
          (a, b) => new Date(b.createdAt) - new Date(a.createdAt)
        );

        // Take only the last three news items
        const lastThreeNews = response.data.slice(0, 3);

        this.cards = lastThreeNews.map((item) => ({
          ...item,
          // Directly assign the transformed URL to imgPath
          imgPath: item.imgPath,
        }));
      } catch (error) {
        console.error("Error fetching news:", error);
      }
    },
    async fetchText() {
      try {
        const response = await axios.get(
          "http://localhost:3000/api/text/661e16febaea5955518ee025",
          {
            withCredentials: true,
          }
        );

        // Assuming the response contains a property named "text"
        this.text = response.data.text;
        console.log(response.data.text);
      } catch (error) {
        console.error("Error fetching text:", error);
      }
    },
  },
};
</script>

<style scoped>
.card img {
  max-height: 275px;
  object-fit: cover;
  background-repeat: no-repeat;
  background-repeat: no-repeat;
}

.text-truncate {
  -webkit-line-clamp: 3;
  -webkit-box-orient: vertical;
  text-overflow: ellipsis;
}
</style>
