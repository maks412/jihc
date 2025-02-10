<template>
  <section id="info " class="my-5 container">
    <div class="row">
      <div
        class="col-lg-6 col-md-6 col-sm-6 justify-content-center text-left infoS"
      >
        <h3 class="h1" style="color: #0077ff">
          {{ $t("JumbotronH1P1") }}<br />
          {{ $t("JumbotronH1P2") }}<br />
          {{ $t("JumbotronH1P3") }}
        </h3>
        <hr />
        <p class="">
          {{ $t("JumbotronP1P1") }}
        </p>
        <p>
          {{ $t("JumbotronP1P2") }}
        </p>
        <p>
          {{ $t("JumbotronP1P3") }}
        </p>
        <p>
          {{ $t("JumbotronP1P4") }} <br />
          {{ $t("JumbotronP1P5") }}
        </p>
      </div>
      <div
        class="col-lg-6 col-md-6 col-sm-6 align-self-center justify-content-end d-flex"
      >
        <img
          src="../assets/dir.jpeg"
          alt=""
          class="img-fluid rounded mx-auto"
          style="height: 600px"
        />
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
