<script>
import Hero2 from "../components/Hero2.vue";
import Career from "../components/Career.vue";

export default {
  name: "App",
  components: {
    Hero2,
    Career,
  },
};
</script>
<template>
  <hero2 title="Карьера" podtitle="Главная / Карьера" />
  <Career />
</template>
