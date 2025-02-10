<template>
  <div class="container pt-5">
    <p>
      {{ $t("WorkP1") }}
    </p>
    <p>
      {{ $t("WorkP2") }}
    </p>

    <p>
      {{ $t("WorkP3") }}
    </p>
    <p>{{ $t("WorkP4") }}</p>

    <div class="album py-5">
      <div class="container">
        <div class="row g-1">
          <div class="col">
            <img src="../assets/educon.png" class="img-fluid" alt="" />
          </div>
          <div class="col">
            <img src="../assets/125.png" class="img-fluid" alt="" />
          </div>
          <div class="col">
            <img src="../assets/ktl.png" class="img-fluid" alt="" />
          </div>
          <div class="col">
            <img src="../assets/trurtwise.png" class="img-fluid" alt="" />
          </div>
          <div class="col">
            <img src="../assets/tgs.png" class="img-fluid" alt="" />
          </div>
          <div class="col">
            <img src="../assets/sdu.png" class="img-fluid" alt="" />
          </div>
        </div>
      </div>
    </div>

    <p>
      {{ $t("WorkP5") }}
    </p>
    <p>
      {{ $t("WorkP6") }}
      <a href="gaziz.janayev@jihc.kz">gaziz.janayev@jihc.kz</a>
    </p>
  </div>
</template>

<script>
export default {
  name: "Jumbotron2",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
