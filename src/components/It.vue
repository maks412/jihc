<template>
  <section id="info " class="my-5 container">
    <div class="row">
      <div
        class="col-lg-6 col-md-6 col-sm-6 justify-content-center text-left infoS"
      >
        <h3 style="color: #0077ff">{{ $t("ItH1") }}</h3>
        <hr />
        <p class="">
          {{ $t("ItP1") }}
        </p>
        <ul
          class="navbar-nav justify-content-end flex-grow-1 pe-3 align-self-center d-flex"
        >
          <li class="nav-item me-3">
            <div
              class="nav-link active d-flex align-self-center"
              style="display: list-item; align-items: center"
              aria-current="page"
              href="#"
            >
              <i class="bi m-0 me-2"
                ><img src="../assets/check.png" alt=""
              /></i>
              <p class="m-0">{{ $t("ItLi1") }}</p>
            </div>
          </li>
          <li class="nav-item me-3">
            <div
              class="nav-link active d-flex align-self-center"
              style="display: list-item; align-items: center"
              aria-current="page"
              href="#"
            >
              <i class="bi m-0 me-2"
                ><img src="../assets/check.png" alt=""
              /></i>
              <p class="m-0">{{ $t("ItLi2") }}</p>
            </div>
          </li>
          <li class="nav-item me-3">
            <div
              class="nav-link active d-flex align-self-center"
              style="display: list-item; align-items: center"
              aria-current="page"
              href="#"
            >
              <i class="bi m-0 me-2"
                ><img src="../assets/check.png" alt=""
              /></i>
              <p class="m-0">{{ $t("ItLi3") }}</p>
            </div>
          </li>
          <li class="nav-item me-3">
            <div
              class="nav-link active d-flex align-self-center"
              style="display: list-item; align-items: center"
              aria-current="page"
              href="#"
            >
              <i class="bi m-0 me-2"
                ><img src="../assets/check.png" alt=""
              /></i>
              <p class="m-0">{{ $t("ItLi4") }}</p>
            </div>
          </li>
          <li class="nav-item me-3">
            <div
              class="nav-link active d-flex align-self-center"
              style="display: list-item; align-items: center"
              aria-current="page"
              href="#"
            >
              <i class="bi m-0 me-2"
                ><img src="../assets/check.png" alt=""
              /></i>
              <p class="m-0">{{ $t("ItLi5") }}</p>
            </div>
          </li>
          <li class="nav-item me-3">
            <div
              class="nav-link active d-flex align-self-center"
              style="display: list-item; align-items: center"
              aria-current="page"
              href="#"
            >
              <i class="bi m-0 me-2"
                ><img src="../assets/check.png" alt=""
              /></i>
              <p class="m-0">{{ $t("ItLi6") }}</p>
            </div>
          </li>
        </ul>
      </div>
      <div
        class="col-lg-6 col-md-6 col-sm-6 align-self-center justify-content-end d-flex mt-5"
      >
        <img src="../assets/It.png" alt="" class="img-fluid" />
      </div>
    </div>
  </section>

  <div class="container d-flex justify-content-center">
    <div class="size text-center">
      <h1 class="m-5" style="color: #0077ff">
        {{ $t("ItH2") }}
        <hr />
      </h1>

      <div class="row align-items-center gap-5">
        <div
          class="col d-flex flex-column gap-1 text-center justify-content-center p-4 rounded-4 py-3 align-items-center mx-5"
        >
          <i class="bi"><img src="../assets/Itcard1.png" alt="" /></i>
          <p class="fw-medium">{{ $t("ItCard1") }}</p>
        </div>
        <div
          class="col d-flex flex-column gap-2 text-center justify-content-center p-4 rounded-4 py-3 align-items-center mx-5"
        >
          <i class="bi"><img src="../assets/Itcard2.png" alt="" /></i>
          <p class="fw-medium">{{ $t("ItCard2") }}</p>
        </div>
        <div
          class="col d-flex flex-column gap-2 text-center justify-content-center p-4 rounded-4 py-3 align-items-center mx-5"
        >
          <i class="bi"><img src="../assets/Itcard3.png" alt="" /></i>
          <p class="fw-medium">{{ $t("ItCard3") }}</p>
        </div>
        <div
          class="col d-flex flex-column gap-2 text-center justify-content-center p-4 rounded-4 py-3 align-items-center mx-5"
        >
          <i class="bi"><img src="../assets/Itcard4.png" alt="" /></i>

          <p class="fw-medium">{{ $t("ItCard4") }}</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Jumbotron2",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
