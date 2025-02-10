<script>
import Hero2 from "../components/Hero2.vue";
import corpusA from "../components/corpusA.vue";

export default {
  components: {
    Hero2,
    corpusA,
  },
};
</script>
<template>
  <Hero2
    title="Корпус А (учебный корпус + актовый зал)"
    podtitle="Главная / Корпус А (учебный корпус + актовый зал)"
  />
  <corpusA />
</template>
