<template>
  <header class="app__header">
    <h1>
      <img src="../assets/img/LogoMain.png" /><span class="visually-hidden"
        >Lock N' Roll Promotions</span
      >
    </h1>
    <NavBar />
  </header>
</template>

<style>
.app__header {
  color: var(--color_white);

  display: flex;
  align-items: end;
}

.app__header h1 {
  font-size: var(--f-size-1);
  display: flex;
}

.app__header img {
  width: 120px;
  height: 120px;
  align-self: center;
}

.visually-hidden {
  display: none;
}
</style>
