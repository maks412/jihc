<template>
  <section id="blog" class="text-center color-white bg-img mb-5 size">
    <div class="inner-overlay overlay size">
      <div
        class="px-5 py-5 container filt size text-center text-lg-start d-flex align-items-center"
      >
        <h1 class="container display-5 lh-2 text-white align-bottom">
          {{ $t("HeroH1P1") }}<br />
          {{ $t("HeroH1P2") }}
        </h1>
        <img
          v-if="isMdOrLarger"
          class="logo w-25 p-5"
          src="../assets/jihc-logo.png"
          alt="Logo"
        />
      </div>
    </div>
  </section>
</template>

<script>
export default {
  components: {},
  // Component logic goes here
  data() {
    return {
      windowWidth: window.innerWidth,
    };
  },
  computed: {
    isMdOrLarger() {
      return this.windowWidth >= 768; // Show only for md and larger
    },
  },
  mounted() {
    window.addEventListener("resize", this.updateWindowWidth);
  },
  beforeUnmount() {
    window.removeEventListener("resize", this.updateWindowWidth);
  },
  methods: {
    updateWindowWidth() {
      this.windowWidth = window.innerWidth;
    },
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.bg-img {
  background-image: url("@/assets/heroes-bg.png"); /* Adjust the path to your background image */
  background-size: cover;
  object-fit: cover;
  background-repeat: no-repeat;
}

.filt {
  backdrop-filter: blur(4px);
  max-width: 1800px;
}

.overlay {
  width: 100%;
  height: 100%;
  width: 100%;
  height: 100%;
  background: linear-gradient(
    rgba(67, 117, 147, 0.307),
    rgba(0, 0, 0, 0.394)
  ); /* Adjust the opacity by changing the alpha values */
  top: 0;
  left: 0;
}

.size {
  min-height: 460px;
}
@media (max-width: 767px) {
  .size {
    min-height: 200px;
  }
}
</style>
