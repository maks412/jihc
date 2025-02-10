<template>
  <div class="d-flex align-items-center py-4 container">
    <main class="form-signin w-100 m-auto">
      <form @submit.prevent="submitForm">
        <h1 class="h3 mb-3 fw-normal">Заполните все поля ниже</h1>

        <p class="h5 mb-3 fw-normal">KZ</p>
        <div class="form-floating">
          <input
            v-model="kzOldValue"
            type="text"
            class="form-control mb-1"
            id="floatingText"
            placeholder="name@example.com"
          />
          <div v-if="warning" class="alert alert-danger" role="alert">{{ warning }}</div>
          <label for="floatingInput">Старый текст</label>
        </div>
        <div class="form-floating">
          <input
            v-model="kzNewValue"
            type="text"
            class="form-control mb-1"
            id="floatingText"
            placeholder="name@example.com"
          />
          <label for="floatingInput">Новый текст</label>
          <div v-if="warning" class="alert alert-danger" role="alert">{{ warning }}</div>
        </div>

        <p class="h5 mb-3 fw-normal">RU</p>
        <div class="form-floating">
          <input
            v-model="ruOldValue"
            type="text"
            class="form-control mb-1"
            id="floatingText"
            placeholder="name@example.com"
          />
          <label for="floatingInput">Старый текст</label>
          <div v-if="warning" class="alert alert-danger" role="alert">{{ warning }}</div>
        </div>
        <div class="form-floating">
          <input
            v-model="ruNewValue"
            type="text"
            class="form-control mb-1"
            id="floatingText"
            placeholder="name@example.com"
          />
          <label for="floatingInput">Новый текст</label>
          <div v-if="warning" class="alert alert-danger" role="alert">{{ warning }}</div>
        </div>

        <button class="btn btn-primary w-100 py-2" type="submit" @click="handleSubmit">
          Добавить текст
        </button>

        <!-- Display the ID of the new object -->
        <p class="mt-3">ID нового объекта: {{ newObjectId }}</p>
      </form>
    </main>
  </div>
</template>

<script>
import axios from "axios";

export default {
  name: "AddNews",
  data() {
    return {
      kzOldValue: '',
      kzNewValue: '',
      ruOldValue: '',
      ruNewValue: '',
      warning: '',
      newObjectId: null, // Initialize newObjectId
    };
  },
  methods: {
    handleSubmit() {
      if (
        !this.kzOldValue.trim() ||
        !this.kzNewValue.trim() ||
        !this.ruOldValue.trim() ||
        !this.ruNewValue.trim()
      ) {
        this.warning = 'Пожалуйста, заполните все поля';
        return;
      } else if(
        this.kzOldValue.trim() ||
        this.kzNewValue.trim() ||
        this.ruOldValue.trim() ||
        this.ruNewValue.trim()
      ) {
        this.warning = '';
      }
    },

    async getNewsById() {
      const id = this.$route.params.id; // Get the id from route params
      try {
        const response = await axios.get(
          `https://jihc.edu.kz/api/admin/news/${id}`
        );
        this.news = {
          newsTitle: response.data.newsTitle,
          imgPath: response.data.imgPath,
          description: response.data.description,
        };

        document.getElementById("floatingTitle").value =
          response.data.newsTitle;
        document.getElementById("floatingDescription").value =
          response.data.description;
        document.getElementById("floatingImageLink").value =
          response.data.imgPath;
      } catch (error) {
        console.log(`Error get element by id ${error}`);
      }
    },
    async submitForm() {
      // Collecting form data
      const formData = {
        newsTitle: document.getElementById("floatingTitle").value,
        description: document.getElementById("floatingDescription").value,
        imgPath: document.getElementById("floatingImageLink").value,
      };

      const id = this.$route.params.id; // Get the id from route params

      try {
        // Sending PUT request with Axios to update news by ID
        const response = await axios.put(
          `https://jihc.edu.kz/api/admin/news/${id}`,
          formData
        );

        // Check if the update was successful
        if (response.status === 200) {
          console.log("News updated successfully:", response.data);

          // Redirect to the admin page upon success
          this.$router.push({ name: "Admin" }); // Ensure the route name 'Admin' exists in your router configuration
        } else {
          console.error("Failed to update news:", response.status);
        }
      } catch (error) {
        console.error("Error updating news:", error);
      }
    },
  },
};
</script>

<style></style>
