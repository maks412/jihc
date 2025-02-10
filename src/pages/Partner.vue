<script>
import Hero2 from "../components/Hero2.vue";
import Work from "../components/work.vue";

export default {
  name: "App",
  components: {
    Hero2,
    Work,
  },
};
</script>
<template>
  <Hero2 title="Работадателям" podtitle="Главная / Работадателям" />
  <Work />
</template>
