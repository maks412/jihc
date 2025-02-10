<template>
  <nav
    class="navbar navbar-expand-lg rounded-top-4"
    aria-label="Twelfth navbar example"
    data-bs-theme="dark"
  >
    <div class="container-fluid">
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
        <ul class="navbar-nav">
          <li>
            <router-link to="/" exact class="nav-link active" href="#">
              {{ $t("ThirdNavNavItem0") }}
            </router-link>
          </li>

          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle active"
              href="#"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              {{ $t("ThirdNavNavItem1") }}
            </a>
            <ul class="dropdown-menu bg-primary">
              <li>
                <router-link to="/history" exact class="dropdown-item drop-down" href="#">
                  {{ $t("ThirdNavNavItem1Li1") }}
                </router-link>
              </li>
              <li>
                <router-link to="/facts" exact class="dropdown-item text-white drop-down" href="#">
                  {{ $t("ThirdNavNavItem1Li2") }}
                </router-link>
              </li>
              <li>
                <router-link
                  to="/documents"
                  exact
                  class="dropdown-item text-white drop-down"
                  href="#"
                >
                  {{ $t("ThirdNavNavItem1Li3") }}
                </router-link>
              </li>
              <li>
                <router-link
                  to="/comand"
                  exact
                  class="dropdown-item text-white drop-down"
                  href="#"
                  >{{ $t("ThirdNavNavItem1Li4") }}</router-link
                >
              </li>

              <li>
                <router-link to="/board" exact class="dropdown-item text-white drop-down" href="#">{{
                  $t("ThirdNavNavItem1Li6")
                }}</router-link>
              </li>

              <li>
                <router-link to="/AllNews" exact class="dropdown-item text-white drop-down" href="#"
                  >{{ $t("ThirdNavNavItem1Li7") }}</router-link
                >
              </li>
            </ul>
          </li>
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle active"
              href="#"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              {{ $t("ThirdNavNavItem2") }}
            </a>
            <ul class="dropdown-menu bg-primary">
              <li>
                <router-link
                  to="/profession"
                  exact
                  class="dropdown-item text-white drop-down"
                  href="#"
                  >{{ $t("ThirdNavNavItem2Li1") }}</router-link
                >
              </li>
              <li>
                <router-link
                  to="/supplydocuments"
                  exact
                  class="dropdown-item text-white drop-down"
                  href="#"
                  >{{ $t("ThirdNavNavItem2Li2") }}</router-link
                >
              </li>
              <li>
                <router-link
                  to="/translate"
                  exact
                  class="dropdown-item text-white drop-down"
                  href="#"
                  >{{ $t("ThirdNavNavItem2Li3") }}</router-link
                >
              </li>
            </ul>
          </li>
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle active"
              href="#"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              {{ $t("ThirdNavNavItem3") }}
            </a>
            <ul class="dropdown-menu bg-primary">
              <li>
                <router-link to="/it" exact class="dropdown-item text-white drop-down" href="#">{{
                  $t("ThirdNavNavItem3Li1")
                }}</router-link>
              </li>
              <li>
                <router-link
                  to="/accounting"
                  exact
                  class="dropdown-item text-white drop-down"
                  href="#"
                  >{{ $t("ThirdNavNavItem3Li2") }}</router-link
                >
              </li>
              <li>
                <router-link
                  to="/pedogogika"
                  exact
                  class="dropdown-item text-white drop-down"
                  href="#"
                  >{{ $t("ThirdNavNavItem3Li3") }}</router-link
                >
              </li>
            </ul>
          </li>
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle active"
              href="#"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              {{ $t("ThirdNavNavItem4") }}
            </a>
            <ul class="dropdown-menu bg-primary">
              <li>
                <router-link to="/corpus" exact class="dropdown-item text-white drop-down" href="#"
                  >{{ $t("ThirdNavNavItem4Li1") }}</router-link
                >
              </li>
              <li>
                <router-link to="/corpusA" exact class="dropdown-item text-white drop-down" href="#"
                  >{{ $t("ThirdNavNavItem4Li2") }}</router-link
                >
              </li>
              <li>
                <router-link
                  to="/Dormitory"
                  exact
                  class="dropdown-item text-white drop-down"
                  href="#"
                  >{{ $t("ThirdNavNavItem4Li3") }}</router-link
                >
              </li>
              <li>
                <router-link
                  to="/sporthall"
                  exact
                  class="dropdown-item text-white drop-down"
                  href="#"
                  >{{ $t("ThirdNavNavItem4Li4") }}</router-link
                >
              </li>
              <li>
                <router-link to="/football" exact class="dropdown-item text-white drop-down" href="#"
                  >{{ $t("ThirdNavNavItem4Li5") }}</router-link
                >
              </li>
              <li>
                <router-link to="/barbe" exact class="dropdown-item text-white drop-down" href="#"
                  >{{ $t("ThirdNavNavItem4Li6") }}</router-link
                >
              </li>

              <li>
                <router-link
                  to="/canteen"
                  exact
                  class="dropdown-item text-white drop-down"
                  href="#"
                  >{{ $t("ThirdNavNavItem4Li7") }}</router-link
                >
              </li>
              <li>
                <router-link to="/prachka" exact class="dropdown-item text-white drop-down" href="#"
                  >{{ $t("ThirdNavNavItem4Li8") }}</router-link
                >
              </li>
            </ul>
          </li>
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle active"
              href="#"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              {{ $t("ThirdNavNavItem5") }}
            </a>
            <ul class="dropdown-menu bg-primary">
              <li>
                <router-link
                  to="/AcademCalendar"
                  exact
                  class="dropdown-item text-white drop-down"
                  href="#"
                  >{{ $t("ThirdNavNavItem5Li1") }}</router-link
                >
              </li>
              <li>
                <router-link
                  to="/edupage"
                  exact
                  class="dropdown-item text-white drop-down"
                  href="#"
                  >{{ $t("ThirdNavNavItem5Li2") }}</router-link
                >
              </li>
              <li>
                <router-link
                  to="/practica"
                  exact
                  class="dropdown-item text-white drop-down"
                  href="#"
                  >{{ $t("ThirdNavNavItem5Li3") }}</router-link
                >
              </li>

              <li>
                <router-link to="/comit" exact class="dropdown-item text-white drop-down" href="#">{{
                  $t("ThirdNavNavItem5Li6")
                }}</router-link>
              </li>
              <li>
                <router-link
                  to="/studentlife"
                  exact
                  class="dropdown-item text-white drop-down"
                  href="#"
                  >{{ $t("ThirdNavNavItem5Li7") }}</router-link
                >
              </li>
              <li>
                <router-link
                  to="/dormitoryrools"
                  exact
                  class="dropdown-item text-white drop-down"
                  href="#"
                  >{{ $t("ThirdNavNavItem5Li8") }}</router-link
                >
              </li>
            </ul>
          </li>
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle active"
              href="#"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              {{ $t("ThirdNavNavItem6") }}
            </a>
            <ul class="dropdown-menu bg-primary">
              <li>
                <router-link
                  to="/parentcomit"
                  exact
                  class="dropdown-item text-white drop-down"
                  href="#"
                  >{{ $t("ThirdNavNavItem6Li1") }}</router-link
                >
              </li>
              <li>
                <router-link
                  to="/contact"
                  exact
                  class="dropdown-item text-white drop-down"
                  href="#"
                  >{{ $t("ThirdNavNavItem6Li2") }}</router-link
                >
              </li>
              <li>
                <router-link
                  to="/connectionteachers"
                  exact
                  class="dropdown-item text-white drop-down"
                  href="#"
                  >{{ $t("ThirdNavNavItem6Li3") }}</router-link
                >
              </li>
            </ul>
          </li>
          <li>
            <router-link to="/partner" exact class="nav-link active" href="#">{{
              $t("ThirdNavNavItem7")
            }}</router-link>
          </li>
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle active"
              href="#"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              {{ $t("ThirdNavNavItem8") }}
            </a>
            <ul class="dropdown-menu bg-primary">
              <li>
                <router-link
                  to="/association"
                  exact
                  class="dropdown-item text-white drop-down"
                  href="#"
                  >{{ $t("ThirdNavNavItem8Li1") }}</router-link
                >
              </li>
              <li>
                <router-link
                  to="/sponsorship"
                  exact
                  class="dropdown-item text-white drop-down"
                  href="#"
                  >{{ $t("ThirdNavNavItem8Li2") }}</router-link
                >
              </li>
            </ul>
          </li>
          <li>
            <router-link
              to="/googlecalendar"
              exact
              class="nav-link active"
              href="#"
              >{{ $t("ThirdNavNavItem9") }}</router-link
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "MyThirdNavbar",
};
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.navbar {
  background-color: #0077ff;
}

.drop-down {
  background-color: #0077ff;
  color: white;
}

.menu {
  background-color: #0E3DE2;
}

.drop-down:hover {
  background-color: #0E3DE2;
  color: white;
}

.filter {
  filter: brightness(120%);
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
