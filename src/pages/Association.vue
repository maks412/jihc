<script>
import Hero2 from "../components/Hero2.vue";
import Association from "../components/Association.vue";

export default {
  name: "App",
  components: {
    Hero2,
    Association,
  },
};
</script>
<template>
  <hero2 :title="$t('AssocPage.title')" :podtitle="$t('AssocPage.podtitle')" />
  <Association />
</template>
