<template>
  <section id="info " class="my-5 container">
    <div class="row">
      <div
        class="col-lg-6 col-md-6 col-sm-6 justify-content-center text-left infoS pb-5"
      >
        <p class="">
          {{ $t("Edupage") }}
        </p>
        <a href="https://jihc.edupage.org" class="">Edupage</a>
      </div>
      <div
        class="col-lg-6 col-md-6 col-sm-6 align-self-center justify-content-center d-flex"
      >
        <img src="../assets/edu.jpg" alt="" class="img-fluid" />
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Jumbotron2",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
