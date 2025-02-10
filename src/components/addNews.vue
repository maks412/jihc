<template>
  <div class="d-flex align-items-center py-4 container">
    <main class="form-signin w-100 m-auto">
      <form @submit.prevent="submitForm">
        <h1 class="h3 mb-3 fw-normal">Please fill all the inputs</h1>

        <div class="form-floating">
          <input
            type="text"
            class="form-control mb-1"
            id="floatingTitle"
            placeholder="name@example.com"
          />
          <label for="floatingInput">News Title</label>
        </div>
        <div class="form-floating">
          <input
            type="text"
            class="form-control mb-1"
            id="floatingImageLink"
            placeholder="Password"
          />
          <label for="floatingPassword">News Image Link</label>
        </div>
        <div class="form-floating">
          <input
            type="text"
            class="form-control mb-1"
            id="floatingDescription"
            placeholder="Password"
          />
          <label for="floatingPassword">News description</label>
        </div>

        <button class="btn btn-primary w-100 py-2" type="submit">
          Add News
        </button>
      </form>
    </main>
  </div>
</template>

<script>
import axios from "axios";

export default {
  name: "AddNews",
  methods: {
    clearText() {
      document.getElementById("floatingTitle").value = "";
      document.getElementById("floatingDescription").value = "";
      document.getElementById("floatingImageLink").value = "";
    },
    async submitForm() {
      // Collecting form data
      const formData = {
        newsTitle: document.getElementById("floatingTitle").value,
        description: document.getElementById("floatingDescription").value,
        imgPath: document.getElementById("floatingImageLink").value,
      };

      try {
        // Sending POST request with Axios
        await axios.post("https://jihc.edu.kz/api/admin/news/add", formData);

        this.clearText();
        // console.log(response.data);

        // Redirect to the admin page upon success
        this.$router.push({ name: "Admin" }); // Ensure the route name 'Admin' exists in your router configuration
      } catch (error) {
        console.error("Error submitting form:", error);
      }
    },
  },
};
</script>

<style></style>
