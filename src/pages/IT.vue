<script>
import Hero2 from "../components/Hero2.vue";
import It from "../components/It.vue";

export default {
  components: {
    Hero2,
    It,
  },
};
</script>
<template>
  <hero2 :title="$t('ItPage.title')" :podtitle="$t('ItPage.podtitle')" />
  <It />
</template>
