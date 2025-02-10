<script>
import Hero2 from "../components/Hero2.vue";
import Edupage from "../components/Edupage.vue";

export default {
  name: "App",
  components: {
    Hero2,
    Edupage,
  },
};
</script>
<template>
  <hero2 title="Электронный журнал" podtitle="Главная / Электронный журнал" />
  <Edupage />
</template>
