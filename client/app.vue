<template>
  <main class="app__main">
    <NavBar />
    <div class="banner__top">
      <div class="banner__top-img">
        <img src="" alt="cinematic image of grappling">
      </div>
    </div>
    <div class="banner__main">
      <img src="" alt="dark abstract triangle pattern background">

      <div class="banner__main-img">
        text
        <img src="" alt="promotion for upcoming seminar">
      </div>
    </div>
    <div class="banner__bottom">
      <div class="banner__bottom-img">
        <img src="" alt="cinematic image of grappling">
      </div>
    </div>

  </main>
</template>

<style>
.app__main {
  --black_main: #191923;
  --white_main: #f3f3fe;
  background-color: var(--black_main);
  font-size: 16px;
  min-height: 100%;

}
.banner__main {
  background-color: var(--white_main);
  min-height: 400px;
  max-height: 400px;
}
.banner__bottom, .banner__top {
  background-color: var(--black_main);
  min-height: 200px;
}

</style>
