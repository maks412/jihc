<template>
  <div class="d-flex align-items-center py-4 container">
    <main class="form-signin w-100 m-auto">
      <form @submit.prevent="submitForm">
        <h1 class="h3 mb-3 fw-normal">Заполните все поля ниже</h1>

        <p class="h5 mb-3 fw-normal">KZ</p>
        <div class="form-floating">
          <input
            v-model="kzValue"
            type="text"
            class="form-control mb-1"
            id="floatingText"
            placeholder="name@example.com"
          />
          <div v-if="warning" class="alert alert-danger" role="alert">{{ warning }}</div>
          <label for="floatingInput">Tекст</label>
        </div>
        <p class="h5 mb-3 fw-normal">RU</p>
        <div class="form-floating">
          <input
            v-model="ruValue"
            type="text"
            class="form-control mb-1"
            id="floatingText"
            placeholder="name@example.com"
          />
          <label for="floatingInput">Текст</label>
          <div v-if="warning" class="alert alert-danger" role="alert">{{ warning }}</div>
        </div>

        <button class="btn btn-primary w-100 py-2" type="submit" @click="handleSubmit">
          Добавить текст
        </button>

        <!-- Display the ID of the new object -->
        <p class="mt-3" @onsubmit="getTextById">ID нового объекта: {{ newObjectId }}</p>
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
      kzValue: '',
      ruValue: '',
      warning: '',
      id: '',
      newObjectId: null, // Initialize newObjectId
    };
  },
  // mounted() {
  //   axios.get('https://jihc-backend-vercel.vercel.app/').then(response => {this.id = response.data}).catch(error => {console.error(error)})
  // },
  methods: {

    async submitForm() {
      if (!this.kzValue.trim() || !this.ruValue.trim()) {
        this.warning = 'Пожалуйста, заполните все поля';
        return;
      } else if(this.kzValue.trim() || this.ruValue.trim()) {
        this.warning = '';
      }
      // Collecting form data
      const formData = {
        kz_text: this.kzValue,
        rus_text: this.ruValue,
      };

      console.log(formData);

      try {
        // Sending POST request with Axios

        const response = await axios.post(
          "https://jihc-backend-vercel.vercel.app/api/admin/text/add",
           formData
        );
        // Get the ID from the response
        this.newObjectId = response.data._id;

        console.log("New object ID:", this.newObjectId);
        return response.data.id;
      } catch (error) {
        console.error("Error submitting form:", error);
      }
    },
  },
};
</script>

<style></style>
