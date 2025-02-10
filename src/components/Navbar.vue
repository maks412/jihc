<template>
  <nav
    class="navbar bg-primary navbar-expand-lg d-none d-lg-block d-xl-block d-xxl-block rounded-bottom-4"
    data-bs-theme="dark"
  >
    <div class="container-fluid container">
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="true"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item h4">
            <a
              class="nav-link active"
              aria-disabled="true"
              href="https://www.instagram.com/jihc.kz/"
              ><i class="bi bi-instagram"></i
            ></a>
          </li>

          <li class="nav-item h4">
            <a
              class="nav-link active"
              aria-disabled="true"
              href="https://www.facebook.com/jihc_kz/"
              ><i class="bi bi-facebook"></i
            ></a>
          </li>
          <li class="nav-item h4">
            <a
              class="nav-link active"
              aria-disabled="true"
              href="https://www.youtube.com/@jihctv2095"
              ><i class="bi bi-youtube"></i
            ></a>
          </li>
        </ul>
        <a
          class="navbar-brand d-flex justify-content-center align-items-center gap-2"
          href="https://go.2gis.com/vda30k"
        >
          <img class="h4" src="../assets/location.png" alt="" />
          {{ $t("NavbarP1") }}
        </a>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.navbar-brand {
  font-size: 16px;
}
.navbar {
  background-color: #0077ff;
}
</style>
