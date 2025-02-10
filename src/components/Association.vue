<template>
  <section id="info " class="mt-5 container">
    <div class="row">
      <div
        class="col-lg-6 col-md-6 col-sm-6 justify-content-center text-left infoS"
      >
        <h1 style="color: #0077ff">{{ $t("AsoocH1") }}</h1>
        <hr />
        <p class="">
          {{ $t("AssocP2") }}
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
              <i class="bi m-0 me-2"><img src="../assets/like.png" alt="" /></i>
              <p class="m-0">
                {{ $t("AssocP3") }}
              </p>
            </div>
          </li>
          <li class="nav-item me-3">
            <div
              class="nav-link active d-flex align-self-center"
              style="display: list-item; align-items: center"
              aria-current="page"
              href="#"
            >
              <i class="bi m-0 me-2"><img src="../assets/like.png" alt="" /></i>
              <p class="m-0">{{ $t("AssocP4") }}</p>
            </div>
          </li>
          <li class="nav-item me-3">
            <div
              class="nav-link active d-flex align-self-center"
              style="display: list-item; align-items: center"
              aria-current="page"
              href="#"
            >
              <i class="bi m-0 me-2"><img src="../assets/like.png" alt="" /></i>
              <p class="m-0">{{ $t("AssocP5") }}</p>
            </div>
          </li>
          <li class="nav-item me-3">
            <div
              class="nav-link active d-flex align-self-center"
              style="display: list-item; align-items: center"
              aria-current="page"
              href="#"
            >
              <i class="bi m-0 me-2"><img src="../assets/like.png" alt="" /></i>
              <p class="m-0">{{ $t("AssocP6") }}</p>
            </div>
          </li>
          <li class="nav-item me-3">
            <div
              class="nav-link active d-flex align-self-center"
              style="display: list-item; align-items: center"
              aria-current="page"
              href="#"
            >
              <i class="bi m-0 me-2"><img src="../assets/like.png" alt="" /></i>
              <p class="m-0">{{ $t("AssocP7") }}</p>
            </div>
          </li>
          <li class="nav-item me-3">
            <div
              class="nav-link active d-flex align-self-center"
              style="display: list-item; align-items: center"
              aria-current="page"
              href="#"
            >
              <i class="bi m-0 me-2"><img src="../assets/like.png" alt="" /></i>
              <p class="m-0">{{ $t("AssocP8") }}</p>
            </div>
          </li>
        </ul>
        <p class="mt-3">
          Алмаз Анарбеков - Координатор по работе с выпускниками. Email:
          <a href="mailto:almaz.anarbekov@jihc.kz">almaz.anarbekov@jihc.kz</a>
        </p>
      </div>

      <img
        src="../assets/studentlifecard1.png"
        alt=""
        class="col-lg-6 col-md-6 col-sm-6 align-self-center mt-4"
      />
    </div>
    <div class="row mb-2">
      <div class="row container mb-5 d-flex justify-content-center col-md-6">
        <div class="size text-center">
          <h1 class="mt-5" style="color: #0077ff">
            {{ $t("AsoocH2") }}
            <hr />
          </h1>
          <p>
            {{ $t("AssocP9") }}
          </p>
        </div>

        <div
          id="myCarousel"
          class="container carousel slide mt-5"
          data-bs-ride="carousel"
        >
          <div class="carousel-inner">
            <div class="alumni-item active crs-img-11"></div>
          </div>
        </div>
      </div>
      <div class="row container mb-5 d-flex justify-content-center col-md-6">
        <div class="size text-center">
          <h1 class="mt-5" style="color: #0077ff">
            {{ $t("AsoocH3") }}
            <hr />
          </h1>
          <p>
            {{ $t("AssocP10") }}
          </p>
        </div>

        <div
          id="myCarousel"
          class="container carousel slide mt-5"
          data-bs-ride="carousel"
        >
          <div class="carousel-inner">
            <div class="alumni-item active crs-img-21"></div>
          </div>
        </div>
      </div>
    </div>
    <!-- <div class="row mb-2">
      <div class="col-md-6">
        <div
          class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative"
        >
          <div class="col p-4 d-flex flex-column position-static">
            <strong class="d-inline-block mb-2 text-primary-emphasis"
              >World</strong
            >
            <h3 class="mb-0">Featured post</h3>
            <div class="mb-1 text-body-secondary">Nov 12</div>
            <p class="card-text mb-auto">
              This is a wider card with supporting text below as a natural
              lead-in to additional content.
            </p>
            <a href="#" class="icon-link gap-1 icon-link-hover stretched-link">
              Continue reading
              <svg class="bi"><use xlink:href="#chevron-right"></use></svg>
            </a>
          </div>
          <div class="col-auto d-none d-lg-block">
            <svg
              class="bd-placeholder-img"
              width="200"
              height="250"
              xmlns="http://www.w3.org/2000/svg"
              role="img"
              aria-label="Placeholder: Thumbnail"
              preserveAspectRatio="xMidYMid slice"
              focusable="false"
            >
              <title>Placeholder</title>
              <rect width="100%" height="100%" fill="#55595c"></rect>
              <text x="50%" y="50%" fill="#eceeef" dy=".3em">Thumbnail</text>
            </svg>
          </div>
        </div>
      </div>
      <div class="col-md-6">
        <div
          class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative"
        >
          <div class="col p-4 d-flex flex-column position-static">
            <strong class="d-inline-block mb-2 text-success-emphasis"
              >Design</strong
            >
            <h3 class="mb-0">Post title</h3>
            <div class="mb-1 text-body-secondary">Nov 11</div>
            <p class="mb-auto">
              This is a wider card with supporting text below as a natural
              lead-in to additional content.
            </p>
            <a href="#" class="icon-link gap-1 icon-link-hover stretched-link">
              Continue reading
              <svg class="bi"><use xlink:href="#chevron-right"></use></svg>
            </a>
          </div>
          <div class="col-auto d-none d-lg-block">
            <svg
              class="bd-placeholder-img"
              width="200"
              height="250"
              xmlns="http://www.w3.org/2000/svg"
              role="img"
              aria-label="Placeholder: Thumbnail"
              preserveAspectRatio="xMidYMid slice"
              focusable="false"
            >
              <title>Placeholder</title>
              <rect width="100%" height="100%" fill="#55595c"></rect>
              <text x="50%" y="50%" fill="#eceeef" dy=".3em">Thumbnail</text>
            </svg>
          </div>
        </div>
      </div>
    </div> -->

    <div class="row container mb-5">
      <div class="size text-center">
        <h1 class="" style="color: #0077ff">
          {{ $t("AsoocH4") }}
          <hr />
        </h1>
        <p>
          {{ $t("AssocP11") }}
        </p>
      </div>

      <div
        id="mystore"
        class="container carousel slide mt-5"
        data-bs-ride="store"
      >
        <div class="carousel-inner">
          <div class="alumni-item active crs-img-31"></div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Jumbotron2",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.carousel-item {
  height: 360px;
}

.alumni-item {
  height: 500px;
  
}


.crs-img-1 {
  background: url("../assets/Jameco_store/Item1.png");
  background-size: cover;
  background-position: center;
  width: 360px;
}
.crs-img-2 {
  background: url("../assets/Jameco_store/Item2.png");
  background-size: cover;
  background-position: center;
  width: 360px;
}
.crs-img-3 {
  background: url("../assets/Jameco_store/Item3.png");
  background-size: cover;
  background-position: center;
  width: 360px;
}
.crs-img-4 {
  background: url("../assets/Jameco_store/Item4.png");
  background-size: cover;
  background-position: center;
  width: 360px;
}

.crs-img-11 {
  background: url("../assets/meetup.png");
  background-size: cover;
  background-position: center;
  width: 100%;
}
.crs-img-12 {
  background: url("../assets/meetup.png");
  background-size: cover;
  background-position: center;
  width: 100%;
}
.crs-img-13 {
  background: url("../assets/meetup.png");
  background-size: cover;
  background-position: center;
  width: 100%;
}
.crs-img-21 {
  background: url("../assets/event.png");
  background-size: cover;
  background-position: center;
  width: 100%;
}
.crs-img-22 {
  background: url("../assets/event.png");
  background-size: cover;
  background-position: center;
  width: 100%;
}
.crs-img-23 {
  background: url("../assets/event.png");
  background-size: cover;
  background-position: center;
  width: 100%;
}
  .crs-img-31 {
  background: url("../assets/30year.png");
  background-size: cover;
  background-position: center;
  width: 100%;
}
.crs-img-32 {
  background: url("../assets/30year.png");
  background-size: cover;
  background-position: center;
  width: 100%;
}
.crs-img-33 {
  background: url("../assets/30year.png");
  background-size: cover;
  background-position: center;
  width: 100%;
}

@media (max-width: 991px) {
  .carousel-item {
    height: 550px;
  }
  .carousel-control-prev img,
  .carousel-control-next img {
    height: 10%;
  }
}

@media (max-width: 767px) {
  .carousel-item {
    height: 250px;
  }
  .store-item {
    height: 250px;
  }

  .carousel-control-next img {
    height: 8%;
  }
}
</style>
