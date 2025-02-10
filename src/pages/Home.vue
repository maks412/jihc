<script>
import Hero from "../components/Hero.vue";
import Column from "../components/Column.vue";
import Jumbotron from "../components/Jumbotron.vue";
import Column2 from "../components/Column2.vue";
import News from "../components/News.vue";

export default {
  name: "App",
  components: {
    Hero,
    Column,
    Jumbotron,
    Column2,
    News,
  },
};
</script>
<template>
  <hero />
  <Column />
  <jumbotron />
  <column2 />
  <News />
</template>
