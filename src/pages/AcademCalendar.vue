<script>
import Hero2 from "../components/Hero2.vue";
import AcademicCalendar from "../components/AcademicCalendar.vue";

export default {
  name: "App",
  components: {
    Hero2,
    AcademicCalendar,
  },
};
</script>
<template>
  <hero2
    title="Академический календарь"
    podtitle="Главная / Академический календарь"
  />
  <AcademicCalendar />
</template>
