<script>
import ConnectTeacher from "@/components/connectTeacher.vue";
import Hero2 from "../components/Hero2.vue";

export default {
  name: "App",
  components: {
    Hero2,
    ConnectTeacher,
  },
};
</script>
<template>
  <hero2
    title="Связь с преподавателем"
    podtitle="Главная / Связь с преподавателем"
  />
  <ConnectTeacher />
</template>
