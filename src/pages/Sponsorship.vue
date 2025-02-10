<script>
import Sponship from "@/components/sponship.vue";
import Hero2 from "../components/Hero2.vue";

export default {
  name: "App",
  components: {
    Hero2,
    Sponship,
  },
};
</script>
<template>
  <hero2 title="Патреон" podtitle="Главная / Патреон" />
  <Sponship />
</template>
