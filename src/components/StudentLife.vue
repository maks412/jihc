<template>
  <div class="container pt-5">
    <p>
      {{ $t("StuLifeP1") }}
    </p>
    <p>
      {{ $t("StuLifeP2") }}
    </p>
    <p>
      {{ $t("StuLifeP3") }}
    </p>
    <p>
      {{ $t("StuLifeP4") }}
    </p>
    <p>
      <span class="fw-bold">Алишер Жунусов</span> - {{ $t("StuLifeP5") }}
      <a href="mailto:alisher.zhunissov@jihc.kz">alisher.zhunissov@jihc.kz</a>
    </p>
    <p>
      <span class="fw-bold">Азиза Саясатова</span> - {{ $t("StuLifeP6") }}
      <a href="mailto:aziza.sayassatova@jihc.kz">aziza.sayassatova@jihc.kz</a>
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
