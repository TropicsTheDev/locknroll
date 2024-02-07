<template>
  <main class="app__main">
    <NavBar />
    <div class="seminar-img">a</div>
    <footer class="footer">
      <div class="footer-container">footer n shieeeeet</div>
    </footer>
  </main>
</template>

<style>
.app__main {
  --black_main: #191923;
  --white_main: #f3f3fe;
  background-color: var(--black_main);
  font-size: 16px;
}

.seminar-img,
.footer-container {
  background-color: var(--white_main);
}

.seminar-img {
  min-height: min(50vh, 500px);
  width: 50%;
  margin: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.footer-container {
  width: 100%;
  height: 10%;
  position: absolute;
  bottom: 0;
}
</style>
