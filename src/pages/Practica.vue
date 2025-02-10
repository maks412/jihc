<script>
import Hero2 from "../components/Hero2.vue";
import Practic from "../components/Practic.vue";

export default {
  name: "App",
  components: {
    Hero2,
    Practic,
  },
};
</script>
<template>
  <Hero2
    title="Практика , Карьера , Проф. ориентация"
    podtitle="Главная / Практика , Карьера , Проф. ориентация"
  />
  <Practic />
</template>
