<script>
import Hero2 from "../components/Hero2.vue";
import Comand from "../components/Comand.vue";

export default {
  name: "App",
  components: {
    Hero2,
    Comand,
  },
};
</script>
<template>
  <hero2
    :title="$t('ComandPage.title')"
    :podtitle="$t('ComandPage.podtitle')"
  />
  <Comand />
</template>
