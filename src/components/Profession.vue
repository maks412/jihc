<template>
  <div class="container py-5" id="featured-3">
    <h4 class="pb-2 fw-bold" style="color: #0077ff">
      {{ $t("ProfessionDesH1") }}
    </h4>
    <div class="row pb-5 g-4 row-cols-1 row-cols-lg-3">
      <div class="feature col">
        <div
          class="feature-icon d-inline-flex align-items-center justify-content-center text-bg-primary bg-gradient fs-2"
        ></div>
        <h5 class="fw-bold text-body-emphasis">1 КУРС</h5>
        <p>
          {{ $t("ProfessionDesP1") }}
        </p>
      </div>
      <div class="feature col">
        <div
          class="feature-icon d-inline-flex align-items-center justify-content-center text-bg-primary bg-gradient fs-2"
        ></div>
        <h5 class="fw-bold text-body-emphasis">2 КУРС</h5>
        <p>
          {{ $t("ProfessionDesP2") }}
        </p>
      </div>
      <div class="feature col">
        <div
          class="feature-icon d-inline-flex align-items-center justify-content-center text-bg-primary bg-gradient fs-2"
        ></div>
        <h5 class="fw-bold text-body-emphasis">3 КУРС</h5>
        <p>
          {{ $t("ProfessionDesP3") }}
        </p>
      </div>
    </div>
    <h4 class="pb-2 fw-bold" style="color: #0077ff">
      {{ $t("ProfessionDesH2") }}
    </h4>
    <div
      class="d-flex flex-column flex-md-row p-4 gap-4 py-md-5 align-items-center justify-content-start"
    >
      <div class="list-group">
        <div class="list-group-item d-flex gap-3 py-3" aria-current="true">
          <img src="../assets/kz_flag.png" alt="" class="" />
          <div
            class="d-flex gap-2 w-100 justify-content-center align-self-center"
          >
            <div>
              <h6 class="mb-0 fw-bold">
                {{ $t("ProfessionDesP4") }}
              </h6>
            </div>
          </div>
        </div>
        <div class="list-group-item d-flex gap-3 py-3" aria-current="true">
          <img src="../assets/ru_flag.png" alt="twbs" class="flex-shrink-0" />
          <div
            class="d-flex gap-2 w-100 justify-content-center align-self-center"
          >
            <div>
              <h6 class="mb-0 fw-bold">
                {{ $t("ProfessionDesP5") }}
              </h6>
            </div>
          </div>
        </div>
        <div class="list-group-item d-flex gap-3 py-3" aria-current="true">
          <img src="../assets/tu_flag.png" alt="twbs" class="flex-shrink-0" />
          <div
            class="d-flex gap-2 w-100 justify-content-center align-self-center"
          >
            <div>
              <h6 class="mb-0 fw-bold">
                {{ $t("ProfessionDesP6") }}
              </h6>
            </div>
          </div>
        </div>
        <div class="list-group-item d-flex gap-3 py-3" aria-current="true">
          <img src="../assets/eng_flag.png" alt="twbs" class="flex-shrink-0" />
          <div class="d-flex w-100 justify-content-center align-self-center">
            <div>
              <h6 class="mb-0 fw-bold">
                {{ $t("ProfessionDesP7") }}
              </h6>
            </div>
          </div>
        </div>
      </div>
    </div>

    <h4 class="pb-2 fw-bold">{{ $t("ProfessionDesH3") }}</h4>
    <p>
      {{ $t("ProfessionDesP8") }}
    </p>

    <div class="row g-5 py-5">
      <div class="col-md-6">
        <h5>{{ $t("ProfessionDesH4") }}</h5>

        <ol class="list-group list-group-unstyled">
          <li class="list-group-item border-0">
            &#8226; {{ $t("ProfessionDesP9") }}
          </li>
          <li class="list-group-item border-0">
            &#8226; {{ $t("ProfessionDesP10") }}
          </li>
          <li class="list-group-item border-0">
            &#8226; {{ $t("ProfessionDesP11") }}
          </li>
          <li class="list-group-item border-0">
            &#8226; {{ $t("ProfessionDesP12") }}
          </li>
        </ol>
      </div>
      <div class="col-md-6">
        <h5 style="color: #0077ff">{{ $t("ProfessionDesH5") }}</h5>

        <ol class="list-group list-group-unstyled">
          <li class="list-group-item border-0">
            &#8226; {{ $t("ProfessionDesP13") }}
          </li>
          <li class="list-group-item border-0">
            &#8226; {{ $t("ProfessionDesP14") }}
          </li>
          <li class="list-group-item border-0">
            &#8226; {{ $t("ProfessionDesP15") }}
          </li>
          <li class="list-group-item border-0">
            &#8226; {{ $t("ProfessionDesP16") }}
          </li>
        </ol>
      </div>
    </div>
    <div class="row">
      <div class="col-md-8">
        <h6>
          {{ $t("ProfessionDesP17") }}<br /><br />
          {{ $t("ProfessionDesP18") }} <br /><br />
          {{ $t("ProfessionDesP19") }}
        </h6>
      </div>
      <div class="col-md-4">
        <router-link
          to="/it"
          exact
          class="btn btn-primary float-end rounded-4 px-5 py-2 mt-3"
          href="#"
          @click="goToTop"
          >{{ $t("ProfessionDesH8") }}</router-link
        >
      </div>
    </div>
    <!-- #00805E -->
    <h4 class="pb-2 fw-bold pt-5">{{ $t("ProfessionDesH6") }}</h4>
    <p>
      {{ $t("ProfessionDesP20") }}
      <br /><br />
      {{ $t("ProfessionDesP21") }}
    </p>
    <div class="d-flex gap-3 pt-3">
      <img src="..//assets/ACCA.png" alt="" />
      <img
        src="..//assets/1C.png
     "
        alt=""
      />
    </div>
    <div class="col-md-6">
      <h5 style="color: #00805e" class="pt-3">{{ $t("ProfessionDesH5") }}</h5>

      <ol class="list-group list-group-unstyled">
        <li class="list-group-item border-0">&#8226; {{ $t("ProfessionDesP22") }}</li>
        <li class="list-group-item border-0">&#8226; {{ $t("ProfessionDesP23") }}</li>
        <li class="list-group-item border-0">&#8226; {{ $t("ProfessionDesP24") }}</li>
        <li class="list-group-item border-0">&#8226; {{ $t("ProfessionDesP25") }}</li>
      </ol>
    </div>

    <div class="row pt-4">
      <div class="col-md-8">
        <h6>
          {{ $t("ProfessionDesP26") }}
          <br /><br />
          {{ $t("ProfessionDesP27") }}
        </h6>
      </div>
      <div class="col-md-4">
        <router-link
          to="/accounting"
          exact
          class="btn btn-primary float-end rounded-4 px-5 py-2 mt-3"
          href="#"
          @click="goToTop"
          >{{ $t("ProfessionDesH8") }}</router-link
        >
      </div>
    </div>

    <h4 class="pb-2 fw-bold pt-5">{{ $t("ProfessionDesH7") }}</h4>
    <p>
      {{ $t("ProfessionDesP28") }} <br /><br />
      {{ $t("ProfessionDesP29") }}
    </p>
    <div class="d-flex gap-3 pt-3">
      <img src="../assets/image 22.png" alt="" />
      <img
        src="..//assets/image 23.png
     "
        alt=""
      />
    </div>
    <div class="row pt-4">
      <div class="col-md-8">
        <h6>
          {{ $t("ProfessionDesP30") }}
          <br /><br />
          {{ $t("ProfessionDesP31") }}
          <br /><br />
          {{ $t("ProfessionDesP32") }}
        </h6>
      </div>
      <div class="col-md-4">
        <router-link
          to="/pedogogika"
          exact
          class="btn btn-primary float-end rounded-4 px-5 py-2 mt-3"
          href="#"
          @click="goToTop"
          >{{ $t("ProfessionDesH8") }}</router-link
        >
      </div>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    goToTop() {
      // Scroll to the top of the page
      window.scrollTo({
        top: 0,
        behavior: "smooth", // Add smooth scrolling effect
      });
    },
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
