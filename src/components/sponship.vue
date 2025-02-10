<template>
  <section id="info " class="my-5 container">
    <div class="row">
      <div
        class="col-lg-6 col-md-6 col-sm-6 justify-content-center text-left infoS"
      >
        <h1 style="color: #0077ff" class="fw-bold border-buttom">
          Patreon Jameco <br />Alumni
        </h1>
        <p class="">
          {{ $t("Sponship1") }}
        </p>
        <p>
          {{ $t("Sponship2") }}
        </p>
        <a href="https://www.patreon.com/JAMECO_ALUMNI"
          >https://www.patreon.com/JAMECO_ALUMNI</a
        >
        <p>
          {{ $t("Sponship3") }}
          <a href="https://www.instagram.com/jamecoalumni.kz/"
            >https://www.instagram.com/jamecoalumni.kz/</a
          >
        </p>
      </div>

      <div
        class="col-lg-6 col-md-6 col-sm-6 align-self-center justify-content-center d-flex row"
      >
        <img src="../assets/spons.png" alt="" class="img-fluid i" />
        <div class="d-flex">
          <p>
            {{ $t("Sponship4") }}
          </p>
          <img src="../assets/qr.png" class="img-fluid" alt="" />
        </div>
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
<style scoped>
.i {
  max-width: 400px;
  max-height: 400px;
}
</style>
