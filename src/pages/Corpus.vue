<script>
import Hero2 from "../components/Hero2.vue";
import Corpus from "../components/Corpus.vue";

export default {
  name: "App",
  components: {
    Hero2,
    Corpus,
  },
};
</script>
<template>
  <hero2 title="Корпус" podtitle="Главная / Корпус" />
  <Corpus />
</template>
