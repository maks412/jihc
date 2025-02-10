<script>
import Hero2 from "../components/Hero2.vue";
import Dormitory from "../components/Dormitory.vue";

export default {
  name: "App",
  components: {
    Hero2,
    Dormitory,
  },
};
</script>
<template>
  <Hero2
    title="Корпус В + Общежитие"
    podtitle="Главная / Корпус В + Общежитие"
  />

  <Dormitory />
</template>
