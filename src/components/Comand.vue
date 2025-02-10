<template>
  <section class="container my-5">
    <h1 class="m-5 text-center" style="color: #0077ff">
      {{ $t("ComandH2") }}
      <hr />
    </h1>
    <div class="d-flex justify-content-center flex-wrap gap-5 p-2">
      <div class="">
        <div class="card text-white rounded-5 shadow-risen img-area">
          <img
            class="card-img rounded-5"
            src="../assets/jihc/comand/AlisherAgai.avif"
            alt="Card image"
          />
          <div class="d-flex card-img-overlay img-text flex-column">
            <div class="mt-auto">
              <h3 class="card-text font-weight-bold h4">
                <span class="d-flex flex-column md-3 fw-bold">
                  Алишер Бодаубеков
                </span>
              </h3>
              <p class="card-title" style="font-size: 0.9rem">
                {{ $t("ComandP1") }}
              </p>
              <a
                :href="`mailto:alisher.bodaubekov@jihc.kz`"
                class="card-title text-decoration-underline"
                >alisher.bodaubekov@jihc.kz</a
              >
            </div>
          </div>
        </div>
      </div>
      <div class="d-flex">
        <div class="card text-white rounded-5 shadow-risen img-area">
          <img
            class="card-img rounded-5"
            src="../assets/jihc/comand/erzhan-koishibekov.avif"
            alt="Card image"
          />
          <div class="card-img-overlay img-text d-flex flex-column">
            <div class="mt-auto">
              <h3 class="card-text font-weight-bold h4">
                <span class="d-flex flex-column md-3 fw-bold">
                  Ержан Койшибеков
                </span>
              </h3>
              <p class="card-title" style="font-size: 0.9rem">
                {{ $t("ComandP2") }}
              </p>
              <a
                :href="`mailto:erzhan.koishybekov@jihc.kz`"
                class="card-title text-decoration-underline"
                >erzhan.koishybekov@jihc.kz</a
              >
            </div>
          </div>
        </div>
      </div>
      <div class="d-flex">
        <div class="card text-white rounded-5 shadow-risen img-area">
          <img
            class="card-img rounded-5"
            src="../assets/jihc/comand/sarmanov-aidos.avif"
            alt="Card image"
          />
          <div class="card-img-overlay img-text d-flex flex-column">
            <div class="mt-auto">
              <h3 class="card-text font-weight-bold h4">
                <span class="d-flex flex-column md-3 fw-bold">
                  Айдос Сарманов
                </span>
              </h3>
              <p class="card-title" style="font-size: 0.9rem">
                {{ $t("ComandP3") }}
              </p>
              <a
                :href="`mailto:aidos.sarmanov@jihc.kz`"
                class="card-title text-decoration-underline"
                >aidos.sarmanov@jihc.kz</a
              >
            </div>
          </div>
        </div>
      </div>
      <div class="d-flex">
        <div class="card text-white rounded-5 shadow-risen img-area">
          <img
            class="card-img rounded-5"
            src="../assets/jihc/comand/Бақытжан Қазанғапов.avif"
            alt="Card image"
          />
          <div class="card-img-overlay img-text d-flex flex-column">
            <div class="mt-auto">
              <h3 class="card-text font-weight-bold h4">
                <span class="d-flex flex-column md-3 fw-bold">
                  Бақытжан Қазанғапов
                </span>
              </h3>
              <p class="card-title" style="font-size: 0.9rem">
                {{ $t("ComandP4") }}
              </p>
              <a
                :href="`mailto:bakytzhan.kazangapov@jihc.kz`"
                class="card-title text-decoration-underline"
                >bakytzhan.kazangapov@jihc.kz</a
              >
            </div>
          </div>
        </div>
      </div>
      <div class="d-flex">
        <div class="card text-white rounded-5 shadow-risen img-area">
          <img
            class="card-img rounded-5"
            src="../assets/jihc/comand/Ақжан Нұрекеева.avif"
            alt="Card image"
          />
          <div class="card-img-overlay img-text d-flex flex-column">
            <div class="mt-auto">
              <h3 class="card-text font-weight-bold h4">
                <span class="d-flex flex-column md-3 fw-bold">
                  Ақжан Нұрекеева
                </span>
              </h3>
              <p class="card-title" style="font-size: 0.9rem">
                {{ $t("ComandP5") }}
              </p>
              <a
                :href="`mailto:akzhan.nurkeyeva@jihc.kz`"
                class="card-title text-decoration-underline"
                >akzhan.nurkeyeva@jihc.kz</a
              >
            </div>
          </div>
        </div>
      </div>
      <div class="d-flex">
        <div class="card text-white rounded-5 shadow-risen img-area">
          <img
            class="card-img rounded-5"
            src="../assets/jihc/comand/Жолдыбаева Тамара.avif"
            alt="Card image"
          />
          <div class="card-img-overlay img-text d-flex flex-column">
            <div class="mt-auto">
              <h3 class="card-text font-weight-bold h4">
                <span class="d-flex flex-column md-3 fw-bold">
                  Каримбердиева Тамара
                </span>
              </h3>
              <p class="card-title" style="font-size: 0.9rem">
                {{ $t("ComandP6") }}
              </p>
              <a
                :href="`mailto:tamara.zholdybaeva@jihc.kz`"
                class="card-title text-decoration-underline"
                >tamara.zholdybaeva@jihc.kz</a
              >
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="container my-5 d-flex flex-column gap-4">
    <h1 class="m-5 text-center" style="color: #0077ff">
      {{ $t("ComandH3") }}
      <hr />
    </h1>
    <div class="d-flex gap-4 justify-content-center">
      <div class="col d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Кенжебаев Ерлан Бахытұлы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP7") }}
          </p>
          <a
            :href="`mailto:yerlan.kenzhebayev@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >yerlan.kenzhebayev@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Оспанов Максат Болатулы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP8") }}
          </p>
          <a
            :href="`mailto:maksat.ospanov@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >maksat.ospanov@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Исабекова Дарина Өміржанқызы
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP9") }}
          </p>
          <a
            :href="`mailto:darina.issabekova@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >darina.issabekova@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Машанло Ихтина Джумазовна</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP10") }}
          </p>
          <a
            :href="`mailto:ihtina.mashanlo@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >ihtina.mashanlo@jihc.kz</a
          >
        </div>
      </div>
    </div>

    <div class="d-flex gap-4">
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Рахманкулова Гульдана Мадыхановна
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP11") }}
          </p>
          <a
            :href="`mailto:rahmankulova.g@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >rahmankulova.g@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Тоқтар Нұргүл Ауесхановна</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP12") }}
          </p>
          <a
            :href="`mailto:nurgul.toktar@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >nurgul.toktar@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Елеусіз Жансая Оңғарбекқызы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP13") }}
          </p>
          <a
            :href="`mailto:zhansaya.yeleusiz@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >zhansaya.yeleusiz@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Сарымбетова Алия Аскаровна</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP14") }}
          </p>
          <a
            :href="`mailto:aliya.sarymbetova@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >aliya.sarymbetova@jihc.kz</a
          >
        </div>
      </div>
    </div>

    <div class="d-flex gap-4">
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Әмірхан Әлі Әсем</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP15") }}
          </p>
          <a
            :href="`mailto:assem.amirkhan-ali@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >assem.amirkhan-ali@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Джанаев Ғазизбек Курышбекович
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP16") }}
          </p>
          <a
            :href="`mailto:gaziz.janayev@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >gaziz.janayev@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Жүнісбай Ақерке Болатқызы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP17") }}
          </p>
          <a
            :href="`mailto:akerke.zhunisbay@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >akerke.zhunisbay@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Кулмаханбетова Бибинур Ермековна
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP18") }}
          </p>
          <a
            :href="`mailto:bibinur.kulmahanetova@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >bibinur.kulmahanetova@jihc.kz</a
          >
        </div>
      </div>
    </div>

    <div class="d-flex gap-4">
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Сарымбетов Ерболат Аскарович
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP19") }}
          </p>
          <a
            :href="`mailto:yerbolat.sarymbetov@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >yerbolat.sarymbetov@jihc.kz</a
          >
        </div>
      </div>
    </div>
  </section>

  <section class="container my-5 d-flex flex-column gap-4">
    <h1 class="m-5 text-center" style="color: #0077ff">
      {{ $t("ComandH4") }}
      <hr />
    </h1>
    <div class="d-flex gap-4 justify-content-center">
      <div class="col d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #00805a"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Саулебекова Данагуль Мирамбековна
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP20") }}
          </p>
          <a
            :href="`mailto:dana.saulebekova@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >dana.saulebekova@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #00805e"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Бекхалиева Назкен Бакытгалиевна
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP21") }}
          </p>
          <a
            :href="`mailto:nazken.bekkhaliyeva@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >nazken.bekkhaliyeva@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #00805e"
        >
          <p class="fw-bold text-light m-0 ms-1">Қанатқызы Зейнеп</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP22") }}
          </p>
          <a
            :href="`mailto:zeinep.kanatkyzy@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >zeinep.kanatkyzy@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #00805e"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Қырықбаева Замира Дәурбекқызы
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP23") }}
          </p>
          <a
            :href="`mailto:zamira.kyrykbayeva@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >zamira.kyrykbayeva@jihc.kz</a
          >
        </div>
      </div>
    </div>

    <div class="d-flex gap-4">
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #00805e"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Саясатова Азиза Жанатбекқызы
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP24") }}
          </p>
          <a
            :href="`mailto:aziza.sayassatova@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >aziza.sayassatova@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #00805e"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Курманбаева Гулзада Меирбековна
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP25") }}
          </p>
          <a
            :href="`mailto:gulzada.kurmanbayeva@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >gulzada.kurmanbayeva@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #00805e"
        >
          <p class="fw-bold text-light m-0 ms-1">Эмэл Картав</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP26") }}
          </p>
          <a
            :href="`mailto:emel.kartav@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >emel.kartav@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #00805e"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Жолдыбаева Тамара Каримбердиевна
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP27") }}
          </p>
          <a
            :href="`mailto:tamara.zholdybaeva@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >tamara.zholdybaeva@jihc.kz</a
          >
        </div>
      </div>
    </div>
  </section>

  <section class="container my-5 d-flex flex-column gap-4">
    <h1 class="m-5 text-center" style="color: #0077ff">
      {{ $t("ComandH5") }}
      <hr />
    </h1>
    <div class="d-flex gap-4 justify-content-center">
      <div class="col d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #43188a"
        >
          <p class="fw-bold text-light m-0 ms-1">Тулегенова Ғайша Анафияевна</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP28") }}
          </p>
          <a
            :href="`mailto:gaysha.tulegenova@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >gaysha.tulegenova@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #43188a"
        >
          <p class="fw-bold text-light m-0 ms-1">Ахмет Ержан Ерболатұлы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP29") }}
          </p>
          <a
            :href="`mailto:erzhan.ahmet@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >erzhan.ahmet@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #43188a"
        >
          <p class="fw-bold text-light m-0 ms-1">Ахметова Айгерим Кайратовна</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP30") }}
          </p>
          <a
            :href="`mailto:aygerim.akhmetova@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >aygerim.akhmetova@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #43188a"
        >
          <p class="fw-bold text-light m-0 ms-1">Ниязов Мухтар Яхшибаевич</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP31") }}
          </p>
          <a
            :href="`mailto:muhtar.niyazov@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >muhtar.niyazov@jihc.kz</a
          >
        </div>
      </div>
    </div>

    <div class="d-flex gap-4 justify-content-center">
      <div class="gap-3 d-flex justify-content-center">
        <div
          class="gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #43188a"
        >
          <p class="fw-bold text-light m-0 ms-1">Тилентаев Қанат Берикбаевич</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP32") }}
          </p>
          <a
            :href="`mailto:kanat.tilentayev@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >kanat.tilentayev@jihc.kz</a
          >
        </div>
      </div>
      <div class="gap-3 d-flex justify-content-center">
        <div
          class="gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #43188a"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Ахметова Гульнур Абрахимовна
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP33") }}
          </p>
          <a
            :href="`mailto:gulnur.akhmetova@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >gulnur.akhmetova@jihc.kz</a
          >
        </div>
      </div>
    </div>
  </section>

  <section class="container my-5 d-flex flex-column gap-4">
    <h1 class="m-5 text-center" style="color: #0077ff">
      {{ $t("ComandH6") }}
      <hr />
    </h1>
    <div class="d-flex gap-4 justify-content-center">
      <div class="col d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #ff9100"
        >
          <p class="fw-bold text-light m-0 ms-1">Алиева Қаламқас Жанбырқызы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP34") }}
          </p>
          <a
            :href="`mailto:kalamkas.aliyeva@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >kalamkas.aliyeva@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #ff9100"
        >
          <p class="fw-bold text-light m-0 ms-1">Жырғау Баян</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP35") }}
          </p>
          <a
            :href="`mailto:bayan.zhyrgau@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >bayan.zhyrgau@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #ff9100"
        >
          <p class="fw-bold text-light m-0 ms-1">Нұрекеева Ақжан Еркінқызы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP36") }}
          </p>
          <a
            :href="`mailto:akzhan.nurkeyeva@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >akzhan.nurkeyeva@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #ff9100"
        >
          <p class="fw-bold text-light m-0 ms-1">Бейсембек Ажар Канаткызы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP37") }}
          </p>
          <a
            :href="`mailto:azhar.beisembek@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >azhar.beisembek@jihc.kz</a
          >
        </div>
      </div>
    </div>

    <div class="d-flex gap-4 justify-content-end">
      <div class="col gap-3 d-flex justify-content-end">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #ff9100"
        >
          <p class="fw-bold text-light m-0 ms-1">Қалдыбек Бөкейхан Мұхтарұлы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP38") }}
          </p>
          <a
            :href="`mailto:bokeikhan.qaldybek@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >bokeikhan.qaldybek@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-center">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #ff9100"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Койшибеков Ержан Аманжолович
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP39") }}
          </p>
          <a
            :href="`mailto:erzhan.koishybekov@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >erzhan.koishybekov@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #ff9100"
        >
          <p class="fw-bold text-light m-0 ms-1">Азамат Тұмар Азаматқызы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP40") }}
          </p>
          <a
            :href="`mailto:tumar.azamat@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >tumar.azamat@jihc.kz</a
          >
        </div>
      </div>
    </div>
  </section>

  <section class="container my-5 d-flex flex-column gap-4">
    <h1 class="m-5 text-center" style="color: #0077ff">
      {{ $t("ComandH7") }}
      <hr />
    </h1>
    <div class="d-flex gap-4 justify-content-center">
      <div class="col d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Мыктыбаев Бахытжан Курбанович
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP41") }}
          </p>
          <a
            :href="`mailto:bakhytzhan.myktybayev@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >bakhytzhan.myktybayev@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Тəжібаева Жансая Әбуқызы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP42") }}
          </p>
          <a
            :href="`mailto:zhansaya.tazhibayeva@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >zhansaya.tazhibayeva@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Егембердиева Мадина Мелисовна
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP43") }}
          </p>
          <a
            :href="`mailto:madina.egemberdieva@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >madina.egemberdieva@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Жүнісов Əлишер Ғалымжанұлы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP44") }}
          </p>
          <a
            :href="`mailto:alisher.zhunissov@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >alisher.zhunissov@jihc.kz</a
          >
        </div>
      </div>
    </div>

    <div class="d-flex gap-4">
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Алекулов Жангерхан Серикович
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP45") }}
          </p>
          <a
            :href="`mailto:zhangerkhan.alekulov@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >zhangerkhan.alekulov@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Сағындық Нұржан Нұрмұратұлы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP46") }}
          </p>
          <a
            :href="`mailto:nurzhan.sagyndyq@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >nurzhan.sagyndyq@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Жаныбек Айбол Жаныбекұлы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP47") }}
          </p>
          <a
            :href="`mailto:aibol.zhanybek@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >aibol.zhanybek@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Мейрам Мерей Бейбітұлы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP48") }}
          </p>
          <a
            :href="`mailto:merey.meiram@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >merey.meiram@jihc.kz</a
          >
        </div>
      </div>
    </div>

    <div class="d-flex gap-4">
      <div class="col gap-3 d-flex justify-content-end">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Тоқтасын Олжас Тоқтарбекұлы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP49") }}
          </p>
          <a
            :href="`mailto:olzhas.toktassyn@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >olzhas.toktassyn@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-center">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Анарбеков Алмаз Нурболұлы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP50") }}
          </p>
          <a
            :href="`mailto:almaz.anarbekov@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >almaz.anarbekov@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Қазанғапов Бақытжан Айтуғанұлы
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP51") }}
          </p>
          <a
            :href="`mailto:bakytzhan.kazangapov@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >bakytzhan.kazangapov@jihc.kz</a
          >
        </div>
      </div>
    </div>
  </section>

  <section class="container my-5 d-flex flex-column gap-4">
    <h1 class="m-5 text-center" style="color: #0077ff">
      {{ $t("ComandH8") }}
      <hr />
    </h1>
    <div class="d-flex gap-4 justify-content-center">
      <div class="col d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #00a353"
        >
          <p class="fw-bold text-light m-0 ms-1">Бердибаева Айжан Амантаевна</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP52") }}
          </p>
          <a
            :href="`mailto:aizhan.berdibayeva@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >aizhan.berdibayeva@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #00a353"
        >
          <p class="fw-bold text-light m-0 ms-1">Тұрар Қарлығаш Қайратқызы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP53") }}
          </p>
          <a
            :href="`mailto:qarlygash.turar@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >qarlygash.turar@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #00a353"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Кудайбергенов Ернар Кайратович
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP54") }}
          </p>
          <a
            :href="`mailto:yernar.kudaibergenov@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >yernar.kudaibergenov@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #00a353"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Куандыкова Нурипа Таласбаевна
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("Comand55") }}
          </p>
          <a
            :href="`mailto:nuripa.kuandykova@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >nuripa.kuandykova@jihc.kz</a
          >
        </div>
      </div>
    </div>

    <div class="d-flex gap-4 justify-content-center">
      <div class="gap-3 d-flex justify-content-center">
        <div
          class="gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #00a353"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Алтынбекова Шынар Жұмабекқызы
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP56") }}
          </p>
          <a
            :href="`mailto:shynar.altynbekova@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >shynar.altynbekova@jihc.kz</a
          >
        </div>
      </div>
      <div class="gap-3 d-flex justify-content-center">
        <div
          class="gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #00a353"
        >
          <p class="fw-bold text-light m-0 ms-1">Айткүл Аппасова</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP57") }}
          </p>
          <a
            :href="`mailto:aitkul.appasova@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >aitkul.appasova@jihc.kz</a
          >
        </div>
      </div>
    </div>
  </section>

  <section class="container my-5 d-flex flex-column gap-4">
    <h1 class="m-5 text-center" style="color: #0077ff">
      {{ $t("ComandH9") }}
      <hr />
    </h1>
    <div class="d-flex gap-4 justify-content-center">
      <div class="col d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Абдуллаева Жансая Тимурқызы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP58") }}
          </p>
          <a
            :href="`mailto:zhansaya.abdullayeva@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >zhansaya.abdullayeva@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Балтабай Нұрбибі Серікқызы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP58") }}
          </p>
          <a
            :href="`mailto:nurbibi.baltabai@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >nurbibi.baltabai@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Дүйсенбай Назерке Дінмұхамедқызы
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP58") }}
          </p>
          <a
            :href="`mailto:nazerke.duisenbai@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >nazerke.duisenbai@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Салқанова Нұрдана Талғатқызы
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP58") }}
          </p>
          <a
            :href="`mailto:nurdana.salkanova@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >nurdana.salkanova@jihc.kz</a
          >
        </div>
      </div>
    </div>

    <div class="d-flex gap-4">
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Мусабаева Ұлжан Абдигаппарқызы
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP58") }}
          </p>
          <a
            :href="`mailto:ulzhan.musabaeva@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >ulzhan.musabaeva@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Ермаханова Айдана Жарқынханқызы
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP58") }}
          </p>
          <a
            :href="`mailto:aidana.yermakhanova@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >aidana.yermakhanova@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Әкім Ырыс Әшімқызы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP58") }}
          </p>
          <a
            :href="`mailto:yrys.akim@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >yrys.akim@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Божбанбай Нұрай Арманқызы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP58") }}
          </p>
          <a
            :href="`mailto:nurai.bozhbanbai@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >nurai.bozhbanbai@jihc.kz</a
          >
        </div>
      </div>
    </div>

    <div class="d-flex gap-4">
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Естемес Тоқжан Мұхитқызы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP58") }}
          </p>
          <a
            :href="`mailto:tokzhan.estemes@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >tokzhan.estemes@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Алтынбекова Ақерке Нұрланқызы
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP58") }}
          </p>
          <a
            :href="`mailto:akerke.altynbekova@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >akerke.altynbekova@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Мактабаева Сымбат Муратбековна
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP58") }}
          </p>
          <a
            :href="`mailto:maktabayeva.symbat@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >maktabayeva.symbat@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Абдылдаева Ақмарал Нұрланқызы
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP58") }}
          </p>
          <a
            :href="`mailto:akmaral.abdyldaeva@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >akmaral.abdyldaeva@jihc.kz</a
          >
        </div>
      </div>
    </div>

    <div class="d-flex gap-4">
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Балтабай Әкімжан Сакенұлы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP58") }}
          </p>
          <a
            :href="`mailto:akimzhan.baltabay@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >akimzhan.baltabay@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Марат Арсен Асқарұлы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP58") }}
          </p>
          <a
            :href="`mailto:arsen.marat@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >arsen.marat@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Жұмабай Бекзат Берікұлы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP58") }}
          </p>
          <a
            :href="`mailto:bekzat.zhumabay@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >bekzat.zhumabay@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Ерғали Айдос Ерғалиұлы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP58") }}
          </p>
          <a
            :href="`mailto:aidos.yergali@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >aidos.yergali@jihc.kz</a
          >
        </div>
      </div>
    </div>

    <div class="d-flex gap-4">
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Елшібек Жандос Маратұлы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP58") }}
          </p>
          <a
            :href="`mailto:zhandos.yelshibek@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >zhandos.yelshibek@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Өмірзақ Бекзат</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP58") }}
          </p>
          <a
            :href="`mailto:bekzat.omirzak@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >bekzat.omirzak@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Қадырбек Мақсат Ерболатұлы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP58") }}
          </p>
          <a
            :href="`mailto:maksat.kadyrbek@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >maksat.kadyrbek@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Абдурашидов Давронбек Мухитдинович
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP58") }}
          </p>
          <a
            :href="`mailto:davronbek.abdurashidov@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >davronbek.abdurashidov@jihc.kz</a
          >
        </div>
      </div>
    </div>

    <div class="d-flex gap-4">
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Даулетұлы Даниал</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP58") }}
          </p>
          <a
            :href="`mailto:danial.dauletuly@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >danial.dauletuly@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">
            Әбзелбек Ағасұлтан Нұрғалиұлы
          </p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP58") }}
          </p>
          <a
            :href="`mailto:agasultan.abzelbek@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >agasultan.abzelbek@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Гулиев Бахтияр Махаматович</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP58") }}
          </p>
          <a
            :href="`mailto:bakhtiyar.guliyev@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >bakhtiyar.guliyev@jihc.kz</a
          >
        </div>
      </div>
      <div class="col gap-3 d-flex justify-content-start">
        <div
          class="col gap-3 rounded-5 p-4 frame d-flex flex-column"
          style="background-color: #0077ff"
        >
          <p class="fw-bold text-light m-0 ms-1">Ашимбеков Алмас Талғатұлы</p>
          <p class="fw-medium text-light p-0 m-0 ms-1 job">
            {{ $t("ComandP58") }}
          </p>
          <a
            :href="`mailto:almas.ashimbekov@jihc.kz`"
            class="ms-1 fw-medium text-light"
            >almas.ashimbekov@jihc.kz</a
          >
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
          imgPath: require("../assets/jihc/comand/AlisherAgai.avif"),
          jobTitle: "Директор",
          name: "Алишер Бодаубеков",
          email: "alisher.bodaubekov@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/erzhan-koishibekov.avif"),
          jobTitle: "Заместитель директора по учебно-методической работе",
          jobTitlekz: "Директордың оқу-әдістемелік жұмысы жөніндегі орынбасары",
          name: "Ержан Койшибеков",
          email: "erzhan.koishybekov@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/sarmanov-aidos.avif"),
          jobTitle: "Заместитель директора по воспитательной работе",
          name: "Айдос Сарманов",
          email: "aidos.sarmanov@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Бақытжан Қазанғапов.avif"),
          jobTitle: "Заместитель директора по воспитательной работе",
          name: "Бақытжан Қазанғапов",
          email: "bakytzhan.kazangapov@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Ақжан Нұрекеева.avif"),
          jobTitle: "Заместитель директора по воспитательной работе",
          name: "Ақжан Нұрекеева",
          email: "akzhan.nurkeyeva@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Жолдыбаева Тамара.avif"),
          jobTitle: "Заместитель директора по воспитательной работе",
          name: "Каримбердиева Тамара",
          email: "tamara.zholdybaeva@jihc.kz",
        },
        /*   {
          imgPath: require("../assets/jihc/comand/Нұржан Сағындық.avif"),
          jobTitle: "Учитель IT",
          name: "Нұржан Сағындық",
          email: "nurzhan.sagyndyq@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Саулебекова Данагуль.avif"),
          jobTitle: "Учитель английского языка ",
          name: "Данагуль Саулебекова",
          email: "danagul.saulebekova@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Айжан Бердибаева.avif"),
          jobTitle: "Учитель учета и аудита",
          name: "Айжан Бердибаева",
          email: "aizhan.berdibayeva@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Анарбеков Алмаз.avif"),
          jobTitle: "Учитель IT",
          name: "Алмаз Анарбеков",
          email: "almaz.anarbekov@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Тоқтасын-Олжас.avif"),
          jobTitle: "Учитель IT",
          name: "Олжас Тоқтасын",
          email: "olzhas.toktassyn@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Жүнісов Əлишер .avif"),
          jobTitle: "Учитель IT",
          name: "Әлишер Жүнісов",
          email: "alisher.zhunissov@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Бахытжан Мыктыбаев.avif"),
          jobTitle: "Учитель IT",
          name: "Бахытжан Мықтыбаев",
          email: "bakhytzhan.myktybayev@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Жаныбек Айбол .avif"),
          jobTitle: "Учитель IT",
          name: "Айбол Жаныбек",
          email: "aibol.zhanybek@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Алекулов Жангерхан.avif"),
          jobTitle: "Учитель IT",
          name: "Жангерхан Алекулов",
          email: "zhangerkhan.alekulov@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Жүрсін Дархан.avif"),
          jobTitle: "Учитель IT",
          name: "Дархан Жүрсін",
          email: "darkhan.zhursin@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Егембердиева Мадина .avif"),
          jobTitle: "Учитель IT",
          name: "Мадина Егембердиева",
          email: "madina.egemberdieva@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Тəжібаева-Жансая.avif"),
          jobTitle: "Учитель IT",
          name: "Жансая Тәжібаева",
          email: "zhansaya.tazhibayeva@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/MereyAgay.avif"),
          jobTitle: "Учитель ",
          name: "Мерей Мейрам",
          email: "merey.meiram@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Қарлығаш Тұрар .avif"),
          jobTitle: "Учитель IT",
          name: "Қарлығаш Тұрар",
          email: "qarlygash.turar@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Ернар Кудайбергенов .avif"),
          jobTitle: "Учитель экономики ",
          name: "Ернар Кудайбергенов",
          email: "yernar.kudaibergenov@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Нұргүл Тоқтар .avif"),
          jobTitle: "Учитель ",
          name: "Нұргүл Тоқтар",
          email: "nurgul.toktar@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Шынар-Алтынбекова.avif"),
          jobTitle: "Учитель менеджмента",
          name: "Шынар Алтынбекова",
          email: "shynar.altynbekova@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Нурипа Куандыкова .avif"),
          jobTitle: "Учитель",
          name: "Нурипа Куандыкова",
          email: "nuripa.kuandykova@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Емел Картав.avif"),
          jobTitle: "Учитель турецкого языка ",
          name: "Емел Картав",
          email: "emel.kartav@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Зейнеп Қанатқызы .avif"),
          jobTitle: "Учитель английского языка ",
          name: "Зейнеп Қанатқызы",
          email: "zeinep.kanatkyzy@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Азиза Саясатова.avif"),
          jobTitle: "Учитель английского языка ",
          name: "Азиза Саясатова",
          email: "aziza.sayassatova@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Назкен Бекхалиева .avif"),
          jobTitle: "Учитель английского языка ",
          name: "Назкен Бекхалиева",
          email: "nazken.bekkhaliyeva@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Замира Қырықбаева .avif"),
          jobTitle: "Учитель английского языка ",
          name: "Замира Қырықбаева",
          email: "zamira.kyrykbayeva@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Бөкейхан Қалдыбек.avif"),
          jobTitle: "Учитель физики",
          name: "Бөкейхан Қалдыбек",
          email: "bokeikhan.qaldybek@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Қаламқас Алиева .avif"),
          jobTitle: "Учитель математики",
          name: "Қаламқас Алиева",
          email: "kalamkas.aliyeva@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Баян Жырғау.avif"),
          jobTitle: "Учитель математики",
          name: "Баян Жырғау",
          email: "bayan.zhyrgau@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Ғазизбек Курышбекович.avif"),
          jobTitle: "Учитель ",
          name: "Ғазизбек Курышбекович",
          email: "gaziz.janayev@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Әмірхан Әлі Әсем .avif"),
          jobTitle: "Психолог ",
          name: "Әсем Әмірхан Әлі",
          email: "assem.amirkhan-ali@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Ержан Ахмет.avif"),
          jobTitle: "Учитель истории ",
          name: "Ержан Ахмет",
          email: "erzhan.ahmet@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Ғайша Тулегенова.avif"),
          jobTitle: "Учитель истории",
          name: "Ғайша Тулегенова",
          email: "gaysha.tulegenova@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Тұмар-Азамат.avif"),
          jobTitle: "Учитель биологии ",
          name: "Тұмар Азамат",
          email: "tumar.azamat@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Ажар Бейсембек.avif"),
          jobTitle: "Учитель химии",
          name: "Ажар Бейсембек",
          email: "azhar.beisembek@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Айгерим Ахметова.avif"),
          jobTitle: "Учитель географии",
          name: "Айгерим Ахметоваи",
          email: "aygerim.akhmetova@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Гулзада Курманбаева .avif"),
          jobTitle: "Учитель казахского языка ",
          name: "Гулзада Курманбаева",
          email: "gulzada.kurmanbayeva@jihc.kzz",
        },
        {
          imgPath: require("../assets/jihc/comand/Қанат Тилентаев .avif"),
          jobTitle: "Учитель физкультуры",
          name: "Қанат Тилентаев",
          email: "kanat.tilentayev@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Мухтар Ниязов.avif"),
          jobTitle: "Учитель НВП",
          name: "Мухтар Ниязов",
          email: "muhtar.niyazov@jihc.kz",
        },
        {
          imgPath: require("../assets/jihc/comand/Гульнур Ахметова.avif"),
          jobTitle: "Учитель физкультуры",
          name: "Гульнур Ахметова",
          email: "gulnur.akhmetova@jihc.kz",
        }, */
      ],
      cards2: [
        {
          name: "Кенжебаев Ерлан Бахытұлы",
          jobTitle: "Заведующий по хозяйственной части",
          email: "yerlan.kenzhebayev@jihc.kz",
        },
        {
          name: "Оспанов Максат Болатулы",
          jobTitle:
            "Инспектор по кадрам, заместитель директора по связям с общественностью",
          email: "maksat.ospanov@jihc.kz",
        },
        {
          name: "Исабекова Дарина Өміржанқызы",
          jobTitle: "Главный бухгалтер",
          email: "darina.issabekova@jihc.kz",
        },
        {
          name: "Машанло Ихтина Джумазовна",
          jobTitle: "Бухгалтер",
          email: "ihtina.mashanlo@jihc.kz",
        },
        {
          name: "Рахманкулова Гульдана Мадыхановна",
          jobTitle: "Экономист",
          email: "rahmankulova.g@jihc.kz",
        },
        {
          name: "Тоқтар Нұргүл Ауесхановна",
          jobTitle: "Методист, офис - регистратор",
          email: "nurgul.toktar@jihc.kz",
        },
        {
          name: "Елеусіз Жансая Оңғарбекқызы",
          jobTitle: "Секретарь отдела образования",
          email: "zhansaya.yeleusiz@jihc.kz",
        },
        {
          name: "Сарымбетова Алия Аскаровна",
          jobTitle: "Социальный педагог",
          email: "aliya.sarymbetova@jihc.kz",
        },
        {
          name: "Әмірхан Әлі Әсем",
          jobTitle: "Психолог",
          email: "assem.amirkhan-ali@jihc.kz",
        },
        {
          name: "Джанаев Ғазизбек Курышбекович",
          jobTitle: "Руководитель отдела планирования карьеры",
          email: "gaziz.janayev@jihc.kz",
        },
        {
          name: "Жүнісбай Ақерке Болатқызы",
          jobTitle: "Медсестра",
          email: "akerke.zhunisbay@jihc.kz",
        },
        {
          name: "Кулмаханбетова Бибинур Ермековна",
          jobTitle: "Библиотекарь",
          email: "bibinur.kulmahanetova@jihc.kz",
        },
        {
          name: "Сарымбетов Ерболат Аскарович",
          jobTitle: "Системный администратор - программист",
          email: "yerbolat.sarymbetov@jihc.kz",
        },
      ],
      cards3: [
        {
          name: "Саулебекова Данагуль Мирамбековна",
          jobTitle: "Учитель английского языка, руководитель кафедры",
          email: "dana.saulebekova@jihc.kz",
        },
        {
          name: "Бекхалиева Назкен Бакытгалиевна",
          jobTitle: "Учитель английского языка",
          email: "nazken.bekkhaliyeva@jihc.kz",
        },
        {
          name: "Қанатқызы Зейнеп",
          jobTitle: "Учитель английского языка",
          email: "zeinep.kanatkyzy@jihc.kz",
        },
        {
          name: "Қырықбаева Замира Дәурбекқызы",
          jobTitle: "Учитель английского языка",
          email: "zamira.kyrykbayeva@jihc.kz",
        },
        {
          name: "Саясатова Азиза Жанатбекқызы",
          jobTitle: "Учитель английского языка",
          email: "aziza.sayassatova@jihc.kz",
        },
        {
          name: "Курманбаева Гулзада Меирбековна",
          jobTitle: "Учитель казахского языка и литературы",
          email: "gulzada.kurmanbayeva@jihc.kz",
        },
        {
          name: "Эмэл Картав",
          jobTitle: "Учитель турецкого языка",
          email: "emel.kartav@jihc.kz",
        },
        {
          name: "Жолдыбаева Тамара Каримбердиевнаа",
          jobTitle: "Учитель русского языка",
          email: "tamara.zholdybaeva@jihc.kz",
        },
      ],
      cards4: [
        {
          name: "Тулегенова Ғайша Анафияевна",
          jobTitle: "Учитель истории, руководитель кафедры",
          email: "gaysha.tulegenova@jihc.kz",
        },
        {
          name: "Ахмет Ержан Ерболатұлы",
          jobTitle: "Учитель истории",
          email: "erzhan.ahmet@jihc.kz",
        },
        {
          name: "Ахметова Айгерим Кайратовна",
          jobTitle: "Учитель географии",
          email: "aygerim.akhmetova@jihc.kz",
        },
        {
          name: "Ниязов Мухтар Яхшибаевич",
          jobTitle: "Учитель НВП",
          email: "muhtar.niyazov@jihc.kz",
        },
        {
          name: "Тилентаев Қанат Берикбаевич",
          jobTitle: "Учитель физкультуры",
          email: "kanat.tilentayev@jihc.kz",
        },
        {
          name: "Ахметова Гульнур Абрахимовна",
          jobTitle: "Учитель физкультуры",
          email: "gulnur.akhmetova@jihc.kz",
        },
      ],
      cards5: [
        {
          name: "Алиева Қаламқас Жанбырқызы",
          jobTitle: "Учитель математики, руководитель кафедры",
          email: "kalamkas.aliyeva@jihc.kz",
        },
        {
          name: "Жырғау Баян",
          jobTitle: "Учитель математики",
          email: "bayan.zhyrgau@jihc.kz",
        },
        {
          name: "Нұрекеева Ақжан Еркінқызы",
          jobTitle: "Учитель математики",
          email: "akzhan.nurkeyeva@jihc.kz",
        },
        {
          name: "Бейсембек Ажар Канаткызы",
          jobTitle: "Учитель химии",
          email: "azhar.beisembek@jihc.kz",
        },
        {
          name: "Қалдыбек Бөкейхан Мұхтарұлы",
          jobTitle: "Учитель физики",
          email: "bokeikhan.qaldybek@jihc.kz",
        },
        {
          name: "Койшибеков Ержан Аманжолович",
          jobTitle: "Учитель физики",
          email: "erzhan.koishybekov@jihc.kz",
        },
        {
          name: "Азамат Тұмар Азаматқызы",
          jobTitle: "Учитель биологии",
          email: "tumar.azamat@jihc.kz",
        },
      ],
      cards6: [
        {
          name: "Мыктыбаев Бахытжан Курбанович",
          jobTitle: "Учитель ИТ, заместитель директора по ИТ",
          email: "bakhytzhan.myktybayev@jihc.kz",
        },
        {
          name: "Тəжібаева Жансая Әбуқызы",
          jobTitle: "Учитель ИТ, Заведующий общежития",
          email: "zhansaya.tazhibayeva@jihc.kz",
        },
        {
          name: "Егембердиева Мадина Мелисовна",
          jobTitle: "Учитель ИТ",
          email: "madina.egemberdieva@jihc.kz",
        },
        {
          name: "Жүнісов Əлишер Ғалымжанұлы",
          jobTitle: "Учитель ИТ, инспектор по делам молодежи",
          email: "alisher.zhunissov@jihc.kz",
        },
        {
          name: "Алекулов Жангерхан Серикович",
          jobTitle: "Учитель ИТ",
          email: "zhangerkhan.alekulov@jihc.kz",
        },
        {
          name: "Сағындық Нұржан Нұрмұратұлы",
          jobTitle: "Учитель ИТ",
          email: "nurzhan.sagyndyq@jihc.kz",
        },
        {
          name: "Жаныбек Айбол Жаныбекұлы",
          jobTitle: "Учитель ИТ",
          email: "aibol.zhanybek@jihc.kz",
        },
        {
          name: "Мейрам Мерей Бейбітұлы",
          jobTitle: "Учитель ИТ",
          email: "merey.meiram@jihc.kz",
        },
        {
          name: "Тоқтасын Олжас Тоқтарбекұлы",
          jobTitle: "Учитель ИТ, Заведующий общежития",
          email: "olzhas.toktassyn@jihc.kz",
        },
        {
          name: "Анарбеков Алмаз Нурболұлы",
          jobTitle: "Учитель ИТ",
          email: "almaz.anarbekov@jihc.kz",
        },
        {
          name: "Қазанғапов Бақытжан Айтуғанұлы",
          jobTitle: "Учитель ИТ",
          email: "bakytzhan.kazangapov@jihc.kz",
        },
      ],
      cards7: [
        {
          name: "Бердибаева Айжан Амантаевна",
          jobTitle: "Преподаватель по финансам, руководитель кафедры",
          email: "aizhan.berdibayeva@jihc.kz",
        },
        {
          name: "Тұрар Қарлығаш Қайратқызы",
          jobTitle: "Преподаватель по бухгалтерскому учету и 1С",
          email: "qarlygash.turar@jihc.kz",
        },
        {
          name: "Кудайбергенов Ернар Кайратович",
          jobTitle: "Преподаватель экономики и маркетинга",
          email: "yernar.kudaibergenov@jihc.kz",
        },
        {
          name: "Куандыкова Нурипа Таласбаевна",
          jobTitle: "Преподаватель по учету и аудиту",
          email: "nuripa.kuandykova@jihc.kz",
        },
        {
          name: "Алтынбекова Шынар Жұмабекқызы",
          jobTitle: "Преподаватель по менеджменту",
          email: "shynar.altynbekova@jihc.kz",
        },
        {
          name: "Айткүл Аппасова",
          jobTitle: "преподаватель бухгалтерского учета и 1С",
          email: "aitkul.appasova@jihc.kz",
        },
      ],
      cards8: [
        {
          name: "Абдуллаева Жансая Тимурқызы",
          jobTitle: "Воспитатель",
          email: "zhansaya.abdullayeva@jihc.kz",
        },
        {
          name: "Балтабай Нұрбибі Серікқызы",
          jobTitle: "Воспитатель",
          email: "nurbibi.baltabai@jihc.kz",
        },
        {
          name: "Дүйсенбай Назерке Дінмұхамедқызы",
          jobTitle: "Воспитатель",
          email: "nazerke.duisenbai@jihc.kz",
        },
        {
          name: "Салқанова Нұрдана Талғатқызы",
          jobTitle: "Воспитатель",
          email: "nurdana.salkanova@jihc.kz",
        },
        {
          name: "Мусабаева Ұлжан Абдигаппарқызы",
          jobTitle: "Воспитатель",
          email: "ulzhan.musabaeva@jihc.kz",
        },
        {
          name: "Ермаханова Айдана Жарқынханқызы",
          jobTitle: "Воспитатель",
          email: "aidana.yermakhanova@jihc.kz",
        },
        {
          name: "Әкім Ырыс Әшімқызы",
          jobTitle: "Воспитатель",
          email: "yrys.akim@jihc.kz",
        },
        {
          name: "Божбанбай Нұрай Арманқызы",
          jobTitle: "Воспитатель",
          email: "nurai.bozhbanbai@jihc.kz",
        },
        {
          name: "Естемес Тоқжан Мұхитқызы",
          jobTitle: "Воспитатель",
          email: "tokzhan.estemes@jihc.kz",
        },
        {
          name: "Алтынбекова Ақерке Нұрланқызы",
          jobTitle: "Воспитатель",
          email: "akerke.altynbekova@jihc.kz",
        },
        {
          name: "Мактабаева Сымбат Муратбековна",
          jobTitle: "Воспитатель",
          email: "maktabayeva.symbat@jihc.kz",
        },
        {
          name: "Абдылдаева Ақмарал Нұрланқызы",
          jobTitle: "Воспитатель",
          email: "akmaral.abdyldaeva@jihc.kz",
        },
        {
          name: "Балтабай Әкімжан Сакенұлы",
          jobTitle: "Воспитатель",
          email: "akimzhan.baltabay@jihc.kz",
        },
        {
          name: "Марат Арсен Асқарұлы",
          jobTitle: "Воспитатель",
          email: "arsen.marat@jihc.kz",
        },
        {
          name: "Жұмабай Бекзат Берікұлы",
          jobTitle: "Воспитатель",
          email: "bekzat.zhumabay@jihc.kz",
        },
        {
          name: "Ерғали Айдос Ерғалиұлы",
          jobTitle: "Воспитатель",
          email: "aidos.yergali@jihc.kz",
        },
        {
          name: "Елшібек Жандос Маратұлы",
          jobTitle: "Воспитатель",
          email: "zhandos.yelshibek@jihc.kz",
        },
        {
          name: "Өмірзақ Бекзат",
          jobTitle: "Воспитатель",
          email: "bekzat.omirzak@jihc.kz",
        },
        {
          name: "Қадырбек Мақсат Ерболатұлы",
          jobTitle: "Воспитатель",
          email: "maksat.kadyrbek@jihc.kz",
        },
        {
          name: "Абдурашидов Давронбек Мухитдинович",
          jobTitle: "Воспитатель",
          email: "davronbek.abdurashidov@jihc.kz",
        },
        {
          name: "Даулетұлы Даниал",
          jobTitle: "Воспитатель",
          email: "danial.dauletuly@jihc.kz",
        },
        {
          name: "Әбзелбек Ағасұлтан Нұрғалиұлы",
          jobTitle: "Воспитатель",
          email: "agasultan.abzelbek@jihc.kz",
        },
        {
          name: "Гулиев Бахтияр Махаматович",
          jobTitle: "Воспитатель",
          email: "bakhtiyar.guliyev@jihc.kz",
        },
        {
          name: "Ашимбеков Алмас Талғатұлы",
          jobTitle: "Воспитатель",
          email: "almas.ashimbekov@jihc.kz",
        },
      ],
    };
  },
};
</script>

<style scoped>
/*Gradient Shadow */
.img-area {
  text-align: center;
  color: #fff;
  position: relative;
}
.img-area img {
  width: 100%;
  height: auto;
}
.img-text,
.img-area:after {
  width: 100%;
  position: absolute;
  left: 0;
}

.img-area:after {
  content: "";
  height: 100%;
  top: 0;
  transition: 0.5s;
  border-bottom-left-radius: 30px;
  border-bottom-right-radius: 30px;
}
.img-area:hover:after {
  background: linear-gradient(
    to bottom,
    rgba(41, 36, 37, 0.01) 0,
    rgba(41, 36, 37, 0.25) 25%,
    rgba(41, 36, 37, 0.5) 50%,
    rgba(41, 36, 37, 0.75) 75%,
    rgba(41, 36, 37, 0.95) 100%
  );
}
.img-text {
  color: transparent;
  padding: 20px;
  bottom: 0;
  z-index: 1;
  transform: translateY(155px);
  transition: all 0.5s cubic-bezier(0.13, 0.62, 0.81, 0.91) 0s;
}
.img-text h3 {
  font-family: "Courier New", Courier, monospace;
}
.img-area:hover .img-text {
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
</style>
