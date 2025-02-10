<template>
  <div class="container pt-5">
    <p>
      {{ $t("Stuhouse1") }}
    </p>
    <p>
      {{ $t("Stuhouse2") }}
    </p>
    <p>
      {{ $t("Stuhouse3") }}
      <br>
      <a
        href="https://docs.google.com/document/d/1f9mbF-p4tFwo33TbIL1c2Xront0F4Twz-KIqJo9q0F0/edit"
        class="fw-bold"
        >{{ $t("Stuhouse4") }}</a
      >
    </p>
  </div>
</template>

<script>
export default {
  name: "Jumbotron2",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
