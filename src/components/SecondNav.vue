<template>
  <nav class="navbar navbar-expand-lg py-2" aria-label="Twelfth navbar example">
    <div class="container-fluid container">
      <div class="d-flex">
        <router-link to="/" exact class="navbar-brand m-0" href="#">
          <div class="immg2 border-end border-secondary"></div
        ></router-link>
        <a href="https://sdu.edu.kz/language/ru/" class="immg ms-2 mt-1"></a>
      </div>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarsExample10"
        aria-controls="navbarsExample10"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div
        class="collapse navbar-collapse justify-content-md-center"
        id="navbarsExample10"
      >
        <ul
          class="navbar-nav justify-content-end flex-grow-1 pe-3 align-self-center d-flex"
        >
          <li class="nav-item me-3">
            <a
              class="nav-link active d-flex align-self-center"
              style="display: list-item; align-items: center"
              aria-current="page"
              href="mailto:info@jihc.kz"
              ><i class="bi bi-envelope-fill h5 m-0 me-2"></i>
              <p class="m-0">
                {{ $t("SecondNavP1") }}

                <br />
                info@jihc.kz
              </p></a
            >
          </li>
          <li class="nav-item">
            <a
              class="nav-link active d-flex align-self-center"
              style="display: list-item; align-items: center"
              aria-current="page"
              href="tel:8-707-802-00-88"
              ><i class="bi bi-telephone-fill h5 m-0 me-2"></i>
              <p class="m-0">
                {{ $t("SecondNavP2") }}
                <br />
                8-707-802-00-88
              </p></a
            >
          </li>
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle active"
              style="display: list-item; align-items: center"
              href="#"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
              id="lang"
            >
              {{ currentLangName }}
            </a>
            <ul class="dropdown-menu">
              <li>
                <button
                  class="dropdown-item"
                  @click="changeLanguage('kz', 'Қаз')"
                >
                  Қаз
                </button>
              </li>
              <li>
                <button
                  class="dropdown-item"
                  @click="changeLanguage('ru', 'Рус')"
                >
                  Рус
                </button>
              </li>
              <li>
                <button
                  class="dropdown-item"
                  @click="changeLanguage('en', 'Eng')"
                >
                  Eng
                </button>
              </li>
            </ul>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  data() {
    return {
      currentLangName: this.getLangName(this.$i18n.locale),
    };
  },
  mounted() {
    // Set the default language to 'ru'
    this.$i18n.locale = "ru";
    this.currentLangName = this.getLangName("ru");
    this.$root.$emit("changeLocale", "ru");
  },
  methods: {
    changeLanguage(locale, langName) {
      this.$i18n.locale = locale;
      this.currentLangName = langName;
      this.$root.$emit("changeLocale", locale);
    },
    getLangName(locale) {
      if (locale === "kz") {
        return "Қаз";
      } else if (locale === "ru") {
        return "Рус";
      } else if (locale === "en") {
        return "Eng";
      }
      return locale;
    },
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.immg {
  background-image: url("../assets/jihc-logo-sdu-v2.svg");
  height: 35px;
  width: 285px;
  background-repeat: no-repeat;
}

.immg2 {
  background-image: url("../assets/jihc-logo-svg-v1.svg");
  height: 35px;
  width: 130px;
  background-repeat: no-repeat;
}

@media (min-width: 990px) and (max-width: 1225px) {
  .navbar-nav > li > a {
    font-size: 10px;
  }
}
@media (min-width: 1225px) and (max-width: 1380px) {
  .navbar-nav > li > a {
    font-size: 14px;
  }
}
</style>
