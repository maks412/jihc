<template>
  <div class="container pt-5">
    <p>
      {{ $t("AcademicCalendarInfoText") }}
    </p>

    <a
      href="https://docs.google.com/spreadsheets/d/12zDp2-gsfxoysz7-J8PIxPE4xB0yALJp5bcTyGj3dXM/edit#gid=734390112"
      class="link-item"
      >Годовой календарь на 2023-2024 учебный год</a
    >
  </div>
</template>

<script>
export default {
  name: "Jumbotron2",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.link-item {
  display: block;
  overflow-wrap: break-word;
  word-wrap: break-word;
  word-break: break-all;
}
</style>
