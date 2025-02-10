<template>
  <section class="container my-5">
    <h1 class="m-5 text-center" style="color: #0077ff">
      {{ $t("BoardH1") }}
      <hr />
    </h1>
    <div class="d-flex justify-content-center flex-wrap gap-5 p-2">
        <div class="row g-4">
        <div
        >
          <div class="card h-100 text-center p-4">
            <img
              src="../assets/jihc/sovet/card1.png"
              class="card-img-top mx-auto d-block c"
              alt="Profile image"
            />
            <div class="card-body">
              <h5 class="card-title">Игенбаев Алимжан Бекежанович</h5>
              <p class="card-text">{{ $t("BoardP1") }}</p>
            </div>
          </div>
        </div>
      </div>
        <div class="row g-4">
        <div
        >
          <div class="card h-100 text-center p-4">
            <img
              src="../assets/jihc/sovet/card2.png"
              class="card-img-top mx-auto d-block c"
              alt="Profile image"
            />
            <div class="card-body">
              <h5 class="card-title">Лесхан Даурен</h5>
              <p class="card-text">{{ $t("BoardP2") }}</p>
            </div>
          </div>
        </div>
      </div>
        <div class="row g-4">
        <div
        >
          <div class="card h-100 text-center p-4">
            <img
              src="../assets/jihc/sovet/card3.png"
              class="card-img-top mx-auto d-block c"
              alt="Profile image"
            />
            <div class="card-body">
              <h5 class="card-title">Муканов Алмас Джубайұлы</h5>
              <p class="card-text">{{ $t("BoardP2") }}</p>
            </div>
          </div>
        </div>
      </div>
        <div class="row g-4">
        <div
        >
          <div class="card h-100 text-center p-4">
            <img
              src="../assets/jihc/sovet/card4.png"
              class="card-img-top mx-auto d-block c"
              alt="Profile image"
            />
            <div class="card-body">
              <h5 class="card-title">Бермаганбетов Галымбек Темирбекович</h5>
              <p class="card-text">{{ $t("BoardP2") }}</p>
            </div>
          </div>
        </div>
      </div>
        <div class="row g-4">
        <div
        >
          <div class="card h-100 text-center p-4">
            <img
              src="../assets/jihc/sovet/card5.png"
              class="card-img-top mx-auto d-block c"
              alt="Profile image"
            />
            <div class="card-body">
              <h5 class="card-title">Жантаева Ардақ Мықтыбековна</h5>
              <p class="card-text">{{ $t("BoardP2") }}</p>
            </div>
          </div>
        </div>
      </div>
        <div class="row g-4">
        <div
        >
          <div class="card h-100 text-center p-4">
            <img
              src="../assets/jihc/sovet/card6.png"
              class="card-img-top mx-auto d-block c"
              alt="Profile image"
            />
            <div class="card-body">
              <h5 class="card-title">Шалғынбаев Жұмадыл Мурзабекұлы</h5>
              <p class="card-text">{{ $t("BoardP2") }}</p>
            </div>
          </div>
        </div>
      </div>
        <div class="row g-4">
        <div
        >
          <div class="card h-100 text-center p-4">
            <img
              src="../assets/jihc/sovet/card7.png"
              class="card-img-top mx-auto d-block c"
              alt="Profile image"
            />
            <div class="card-body">
              <h5 class="card-title">Джурымбаев Галымжан Бахитжанович</h5>
              <p class="card-text">{{ $t("BoardP2") }}</p>
            </div>
          </div>
        </div>
      </div>
      </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      cards: [
        {
          imgPath: require("../assets/jihc/sovet/card1.png"),
          jobTitle: "Ректор SDU Universitym",
          name: "Игенбаев Алимжан Бекежанович",
          titleBoard: "Председатель попечительского совета",
        },
        {
          imgPath: require("../assets/jihc/sovet/card2.png"),
          jobTitle: "президент ассоциации выпускников колледжа “JAMECO ALUMNI”",
          name: "Лесхан Даурен",
          titleBoard: "Член попечительского совета",
        },
        {
          imgPath: require("../assets/jihc/sovet/card3.png"),
          jobTitle:
            "региональный координатор на Юге Казахстана МОФ “Білім-Инновация”",
          name: "Муканов Алмас Джубайұлы",
          titleBoard: "Член попечительского совета",
        },
        {
          imgPath: require("../assets/jihc/sovet/card4.png"),
          jobTitle: "гражданский активист, международный коуч",
          name: "Бермаганбетов Галымбек Темирбекович",
          titleBoard: "Член попечительского совета",
        },
        {
          imgPath: require("../assets/jihc/sovet/card5.png"),
          jobTitle:
            "старший преподаватель кафедры “Экономика” в Dulaty University”",
          name: "Жантаева Ардақ Мықтыбековна",
          titleBoard: "Член попечительского совета",
        },

        {
          imgPath: require("../assets/jihc/sovet/card6.png"),
          jobTitle: "предприниматель - меценат, учредитель школы “Innoverse”",
          name: "Шалғынбаев Жұмадыл Мурзабекұлы",
          titleBoard: "Член попечительского совета",
        },
        {
          imgPath: require("../assets/jihc/sovet/card7.png"),
          jobTitle: "предприниматель - меценат, учредитель школы “Innoverse”",
          name: "Джурымбаев Галымжан Бахитжанович",
          titleBoard: "Член попечительского совета",
        },

        // Add more card objects as needed
      ],
    };
  },
};
</script>

<style scoped>
.card {
  border: 0;
}
.c {
  max-width: 130px;
}
.img-area {
    text-align: center;
    color: #fff;
    position: relative;
}
.img-area img {
    width: 100%;
    height: auto;
}    
.img-text, .img-area:after {
    width: 100%;
    position: absolute;
    left: 0;
}

.img-area:after {
    content: '';
    height: 100%;
    top: 0;
    transition: .5s;
    border-bottom-left-radius: 30px;
    border-bottom-right-radius: 30px;
}
.img-area:hover:after {
    background: linear-gradient(to bottom, rgba(41, 36, 37, .01) 0, rgba(41, 36, 37, 0.25) 25%, rgba(41, 36, 37, 0.5) 50%, rgba(41, 36, 37, .75) 75%, rgba(41, 36, 37, 0.95) 100%);
}
.img-text {
    color: transparent;
    padding: 20px;
    bottom: 0;
    z-index: 1;
    transform: translateY(155px);
    transition: all .5s  cubic-bezier(.13, .62, .81, .91) 0s;
}
.img-text h3{
    font-family: 'Courier New', Courier, monospace;
}
.img-area:hover .img-text{
    transform: translateY(0);
    color: #fff;
}

.job {
  line-height: 16px;
  font-size: 12px;
}
.frame {
  max-width: 300px;
}
/* Add your component-specific styles here */
.inner-shadow-bottom {
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  height: 100%; /* Adjust the height of the shadow as needed */
  background: linear-gradient(
    0deg,
    rgba(255, 255, 255, 0.3) 0%,
    rgba(255, 255, 255, 0) 100%
  );
  border-radius: inherit;
  pointer-events: none; /* Ensure the pseudo-element doesn't interfere with interaction */
}
.card {
  border: 0 !important;
}
.card {
  position: relative;
}
.card img {
  max-height: 326.25px;
  object-fit: cover; /* Ensures the image doesn't exceed the width of its container */
  width: auto; /* Maintains the aspect ratio */
}
/* Add your component-specific styles here */
</style>
