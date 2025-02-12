<template>
  <div
    id="myCarousel"
    class="container carousel slide mt-5"
    data-bs-ride="carousel"
  >
    <div class="carousel-indicators">
      <button
        type="button"
        data-bs-target="#myCarousel"
        data-bs-slide-to="0"
        class=""
        aria-label="Slide 1"
      ></button>
      <button
        type="button"
        data-bs-target="#myCarousel"
        data-bs-slide-to="1"
        aria-label="Slide 2"
        class=""
      ></button>
      <button
        type="button"
        data-bs-target="#myCarousel"
        data-bs-slide-to="2"
        aria-label="Slide 3"
        class=""
        aria-current="true"
      ></button>
      <button
        type="button"
        data-bs-target="#myCarousel"
        data-bs-slide-to="3"
        aria-label="Slide 4"
        class=""
        aria-current="true"
      ></button>
      <button
        type="button"
        data-bs-target="#myCarousel"
        data-bs-slide-to="4"
        aria-label="Slide 5"
        class=""
        aria-current="true"
      ></button>
      <button
        type="button"
        data-bs-target="#myCarousel"
        data-bs-slide-to="5"
        aria-label="Slide 6"
        class=""
        aria-current="true"
      ></button>
      <button
        type="button"
        data-bs-target="#myCarousel"
        data-bs-slide-to="6"
        aria-label="Slide 7"
        class="active"
        aria-current="true"
      ></button>
      <button
        type="button"
        data-bs-target="#myCarousel"
        data-bs-slide-to="7"
        aria-label="Slide 8"
        class=""
        aria-current="true"
      ></button>
      <button
        type="button"
        data-bs-target="#myCarousel"
        data-bs-slide-to="8"
        aria-label="Slide 9"
        class=""
        aria-current="true"
      ></button>
      <button
        type="button"
        data-bs-target="#myCarousel"
        data-bs-slide-to="9"
        aria-label="Slide 10"
        class=""
        aria-current="true"
      ></button>
      <button
        type="button"
        data-bs-target="#myCarousel"
        data-bs-slide-to="10"
        aria-label="Slide 11"
        class=""
        aria-current="true"
      ></button>
      <button
        type="button"
        data-bs-target="#myCarousel"
        data-bs-slide-to="11"
        aria-label="Slide 12"
        class=""
        aria-current="true"
      ></button>
      <button
        type="button"
        data-bs-target="#myCarousel"
        data-bs-slide-to="12"
        aria-label="Slide 13"
        class=""
        aria-current="true"
      ></button>
    </div>
    <div class="carousel-inner rounded">
      <div class="carousel-item active crs-img-1"></div>
      <div class="carousel-item crs-img-2"></div>
      <div class="carousel-item crs-img-3"></div>
      <div class="carousel-item crs-img-4"></div>
      <div class="carousel-item crs-img-5"></div>
      <div class="carousel-item crs-img-6"></div>
      <div class="carousel-item crs-img-7"></div>
      <div class="carousel-item crs-img-8"></div>
      <div class="carousel-item crs-img-9"></div>
      <div class="carousel-item crs-img-10"></div>
      <div class="carousel-item crs-img-11"></div>
      <div class="carousel-item crs-img-12"></div>
      <div class="carousel-item crs-img-13"></div>
    </div>
    <button
      class="carousel-control-prev"
      type="button"
      data-bs-target="#myCarousel"
      data-bs-slide="prev"
    >
      <img src="../assets/button_prev.png" alt="" />
      <span class="visually-hidden">Previous</span>
    </button>
    <button
      class="carousel-control-next"
      type="button"
      data-bs-target="#myCarousel"
      data-bs-slide="next"
    >
      <img src="../assets/button_next.png" alt="" />
      <span class="visually-hidden">Next</span>
    </button>
  </div>
  <h2 class="m-5 text-center" style="color: #0077ff">Корпус</h2>
  <div class="">
    <div class="container">
      <p class="lead m-0">
        <span class="fw-bold">{{ $t("CorpusPBold") }}</span>
        {{ $t("CorpusP") }}
      </p>
      <p>
        {{ $t("CorpusP2") }}
      </p>
      <p>
        {{ $t("CorpusP3") }}
      </p>
      <p>
        {{ $t("CorpusP4") }}
      </p>
      <p>
        {{ $t("CorpusP5") }}
      </p>
      <p>
        {{ $t("CorpusP6") }}
      </p>
      <p>
        {{ $t("CorpusP7") }}
      </p>
    </div>
  </div>
  <!-- <div class="pt-5 d-flex justify-content-center container">
    <img src="../assets/cor14.png" alt="" class="img-fluid" />
  </div> -->
  <!-- HTML with Bootstrap classes -->

  <div class="container position-relative p-0 text-center map2 mt-5" style="">
    <img
      src="../assets/map2.png"
      alt="College Overview"
      class="img-fluid rounded-5"
    />
    <router-link
      to="/sporthall"
      exact
      class="map-link map-link1 p-2 rounded"
      href="#"
      >СПОРТЗАЛ</router-link
    >
    <router-link
      to="/football"
      exact
      class="map-link map-link2 p-2 rounded"
      href="#"
      >ФУТБОЛЬНОЕ ПОЛЕ</router-link
    >
    <router-link
      to="/Dormitory"
      exact
      class="map-link map-link3 p-2 rounded"
      href="#"
      >КОРПУС В И ОБЩЕЖИТИЕ</router-link
    >
    <router-link
      to="/prachka"
      exact
      class="map-link map-link4 p-2 rounded"
      href="#"
      >ПРАЧЕЧНАЯ</router-link
    >
    <router-link
      to="/barbe"
      exact
      class="map-link map-link5 p-2 rounded"
      href="#"
      >БЕСЕДКА ДЛЯ БАРБЕКЮ</router-link
    >
    <router-link
      to="/canteen"
      exact
      class="map-link map-link6 p-2 rounded"
      href="#"
      >СТОЛОВАЯ</router-link
    >
    <router-link
      to="/canteen"
      exact
      class="map-link map-link7 p-2 rounded"
      href="#"
      >КОРПУС А (учебный <br />корпус + актовый зал)</router-link
    >
  </div>
</template>

<script>
export default {
  data() {
    return {
      imagePath: require("../assets/cor14.png"),
    };
  },
};
</script>

<style scoped>
.map-link1 {
  top: 20.7%;
  font-weight: 600;
  background-color: white;
}
.map-link2 {
  top: 39%;
  background-color: white;
  font-weight: 600;
}
.map-link3 {
  top: 10.3%;
  text-align: start;
  background-color: white;
  font-weight: 600;
}
.map-link4 {
  top: 25%;
  font-weight: 600;
  background-color: white;
}
.map-link5 {
  top: 37%;
  text-align: start;
  font-weight: 600;
  background-color: white;
}
.map-link6 {
  top: 44%;
  font-weight: 600;
  background-color: white;
}
.map-link7 {
  top: 67.5%;
  text-align: start;
  background-color: white;
  font-weight: 600;
}

.map-link {
  position: absolute;
  display: block;
  /* Style your links as needed */
  color: #000;
  text-decoration: none;
  transform: translate(-50%, -50%); /* Adjust as necessary for positioning */
  z-index: 10; /* Ensure the z-index is high enough to be above the image */
}

@media (max-width: 1250px) {
  .map-link1 {
    font-weight: 600;
    left: 29%;
  }
  .map-link2 {
    font-weight: 600;
    left: 25.5%;
  }
  .map-link3 {
    font-weight: 600;
    left: 53%;
  }
  .map-link4 {
    font-weight: 600;
    left: 63%;
  }
  .map-link5 {
    font-weight: 600;
    font-size: 13px;
    left: 49.5%;
  }
  .map-link6 {
    font-weight: 600;
    left: 67.5%;
  }
  .map-link7 {
    font-weight: 600;
    left: 44.5%;
  }
}

@media (max-width: 1200px) {
  .map-link1 {
    font-weight: 600;
    font-size: 15px;
    left: 25%;
  }
  .map-link2 {
    font-weight: 600;
    font-size: 14px;
    left: 21.5%;
  }
  .map-link3 {
    font-weight: 600;
    font-size: 13px;
    left: 53.5%;
  }
  .map-link4 {
    font-weight: 600;
    font-size: 13px;
    left: 65.5%;
  }
  .map-link5 {
    font-weight: 600;
    font-size: 13px;
    left: 45.5%;
  }
  .map-link6 {
    font-weight: 600;
    font-size: 13px;
    left: 70.5%;
  }
  .map-link7 {
    font-weight: 600;
    font-size: 14px;
    left: 44.5%;
  }
}
@media (max-width: 992px) {
  .map-link1 {
    left: 18.5%;
  }
  .map-link2 {
    left: 11.5%;
  }
  .map-link3 {
    left: 55%;
    font-size: 13px;
  }
  .map-link4 {
    left: 70.5%;
    font-size: 13px;
  }
  .map-link5 {
    left: 41.5%;
    font-size: 13px;
  }
  .map-link6 {
    left: 77%;
    font-size: 13px;
  }
  .map-link7 {
    left: 41.5%;
    font-size: 13px;
  }
}
@media (max-width: 769px) {
  .map-link1 {
    font-weight: 600;
    font-size: 13px;
    left: 16.5%;
  }
  .map-link2 {
    font-weight: 600;
    font-size: 11px;
    left: 13.5%;
  }
  .map-link3 {
    font-weight: 600;
    font-size: 10px;
    left: 76.5%;
    flex-wrap: nowrap;
  }
  .map-link4 {
    font-weight: 600;
    font-size: 10px;
    left: 90.5%;
    flex-wrap: nowrap;
  }
  .map-link5 {
    font-weight: 600;
    font-size: 10px;
    left: 49.5%;
    flex-wrap: nowrap;
  }
  .map-link6 {
    font-weight: 600;
    font-size: 10px;
    left: 82.5%;
    flex-wrap: nowrap;
  }
  .map-link7 {
    font-weight: 600;
    font-size: 10px;
    left: 51.5%;
    flex-wrap: nowrap;
  }
}
@media (max-width: 576px) {
  .map-link1 {
    font-weight: 600;
    font-size: 12px;
    left: 22.5%;
  }
  .map-link4 {
    font-weight: 600;
    font-size: 12px;
    left: 90.5%;
  }
}
@media (max-width: 515px) {
  .map-link1 {
    left: 22.5%;
    font-weight: 600;
    font-size: 9px;
  }
  .map-link2 {
    left: 14.5%;
    font-weight: 600;
    font-size: 9px;
  }
  .map-link3 {
    left: 78.5%;
    font-weight: 600;
    font-size: 8px;
    width: 110px;
  }
  .map-link4 {
    left: 90.5%;
    font-weight: 600;
    font-size: 9px;
  }
  .map-link5 {
    font-weight: 600;
    font-size: 9px;
  }
  .map-link6 {
    font-weight: 600;
    font-size: 9px;
  }
  .map-link7 {
    font-weight: 600;
    font-size: 9px;
  }
}
@media (max-width: 430px) {
  .map-link2 {
    font-weight: 600;
    font-size: 8px;
    flex-wrap: nowrap;
    left: 13.7%;
  }
  .map-link3 {
    left: 78.5%;
    font-weight: 600;
    font-size: 8px;
    flex-wrap: nowrap;
  }
  .map-link4 {
    font-weight: 600;
    font-size: 8px;
    flex-wrap: nowrap;
  }
  .map-link5 {
    font-weight: 600;
    font-size: 8px;
    flex-wrap: nowrap;
  }
  .map-link6 {
    font-weight: 600;
    font-size: 8px;
    flex-wrap: nowrap;
  }
  .map-link7 {
    font-weight: 600;
    font-size: 8px;
    flex-wrap: nowrap;
  }
}

@media (min-width: 1250px) {
  .map-link1 {
    left: 32%;
  }
  .map-link2 {
    left: 28%;
  }
  .map-link3 {
    left: 54%;
    top: 9.3%;
  }
  .map-link4 {
    left: 62%;
  }
  .map-link5 {
    left: 45%;
  }
  .map-link6 {
    left: 65%;
  }
  .map-link7 {
    left: 45%;
  }
}

.carousel-item {
  height: 460px;
}

.crs-img-1 {
  background: url("../assets/jihc/корпус/cor1.avif");
  background-size: cover;
  background-position: center;
  width: 100%;
}
.crs-img-2 {
  background: url("../assets/jihc/корпус/cor2.avif");
  background-size: cover;
  background-position: center;
  width: 100%;
}
.crs-img-3 {
  background: url("../assets/jihc/корпус/cor3.avif");
  background-size: cover;
  background-position: center;
  width: 100%;
}
.crs-img-4 {
  background: url("../assets/jihc/корпус/cor4.avif");
  background-size: cover;
  background-position: center;
  width: 100%;
}
.crs-img-5 {
  background: url("../assets/jihc/корпус/cor5.avif");
  background-size: cover;
  background-position: center;
  width: 100%;
}
.crs-img-6 {
  background: url("../assets/jihc/корпус/cor6.avif");
  background-size: cover;
  background-position: center;
  width: 100%;
}
.crs-img-7 {
  background: url("../assets/jihc/корпус/cor7.avif");
  background-size: cover;
  background-position: center;
  width: 100%;
}
.crs-img-8 {
  background: url("../assets/jihc/корпус/cor8.avif");
  background-size: cover;
  background-position: center;
  width: 100%;
}
.crs-img-9 {
  background: url("../assets/jihc/корпус/cor9.avif");
  background-size: cover;
  background-position: center;
  width: 100%;
}
.crs-img-10 {
  background: url("../assets/jihc/корпус/cor10.avif");
  background-size: cover;
  background-position: center;
  width: 100%;
}
.crs-img-11 {
  background: url("../assets/jihc/корпус/cor11.avif");
  background-size: cover;
  background-position: center;
  width: 100%;
}
.crs-img-12 {
  background: url("../assets/jihc/корпус/cor12.avif");
  background-size: cover;
  background-position: center;
  width: 100%;
}
.crs-img-13 {
  background: url("../assets/jihc/корпус/cor13.avif");
  background-size: cover;
  background-position: center;
  width: 100%;
}

@media (max-width: 991px) {
  .carousel-item {
    height: 350px;
  }
  .carousel-control-prev img,
  .carousel-control-next img {
    height: 8%;
  }
}

@media (max-width: 767px) {
  .carousel-item {
    height: 250px;
  }
  .carousel-control-next img {
    height: 8%;
  }
}

/* Custom CSS */
.container-xl.position-relative {
  /* margin-left: auto; */
  /* margin-right: auto; */
}
</style>
