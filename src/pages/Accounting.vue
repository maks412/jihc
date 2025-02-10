<script>
import Hero2 from "../components/Hero2.vue";
import Accounting from "../components/Accounting.vue";

export default {
  name: "App",
  components: {
    Hero2,
    Accounting,
  },
};
</script>
<template>
  <hero2
    :title="$t('accountingPage.title')"
    :podtitle="$t('accountingPage.podtitle')"
  />
  <Accounting />
</template>
