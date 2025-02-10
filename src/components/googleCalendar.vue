<template>
  <div class="container py-5 align-items-center d-flex flex-column">
    <p class="text-center">
      {{ $t("Calendar") }}
    </p>

    <iframe
      src="https://calendar.google.com/calendar/embed?height=600&wkst=2&bgcolor=%23ffffff&ctz=UTC&showTitle=0&showPrint=0&showTabs=0&src=aW5mb0BqaWhjLmt6&src=cnUua3ojaG9saWRheUBncm91cC52LmNhbGVuZGFyLmdvb2dsZS5jb20&color=%23039BE5&color=%230B8043"
      style="border: 0"
      width="1200"
      height="600"
      frameborder="0"
      scrolling="no"
      class="py-3 calen"
    ></iframe>
  </div>
</template>

<script>
export default {
  name: "Jumbotron2",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@media (max-width: 1200px) {
  .calen {
    width: 700px;
  }
}
@media (max-width: 991px) {
  .calen {
    width: 500px;
  }
}

@media (max-width: 576px) {
  .calen {
    width: 350px;
  }
}
</style>
