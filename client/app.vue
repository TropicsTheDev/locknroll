<template>
  <main class="app__main">
    <header class="app__header">
      <h1>Deez Nuts</h1>
      <NavBar />
    </header>
    <section class="featured">
      <h2 class="featured__heading">Featured Event</h2>
      <main class="featured__body">
        <article class="featured__content">
          <h3>Jason Valle</h3>
          <h4>No-Gi Jiu-Jitsu Seminar</h4>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas
            urna nibh, sagittis a scelerisque in, tempor mattis arcu.
            Pellentesque a auctor lacus. Integer lobortis molestie nulla in
            mattis. Maecenas faucibus mi vel orci aliquam vehicula. Vivamus
            pulvinar tempor mauris, ut vestibulum erat placerat sed. Mauris sit
            amet orci est. Donec condimentum ut nibh sed fringilla. Aliquam
            luctus ultricies semper. Mauris elementum, libero ac hendrerit
            molestie, sapien sem egestas dui, vel pharetra lectus odio id ex.
            Nam ultrices consequat luctus. Nulla auctor sem ut est dignissim, in
            accumsan sapien congue. In vel ultrices odio, sed facilisis augue.
          </p>
        </article>
        <aside class="featured__img-wrapper center">
          <img
            class="featured__img fill-container"
            src="assets/styles/img/JasonPoster_Final.jpeg"
            alt="cinematic image of grappling"
          />
        </aside>
      </main>
    </section>
    <section class="past-events">
      <article class="past-events__info"></article>
      <img
        class="past-events__img fill-container"
        src="assets/styles/img/background1.jpg"
        alt="dark abstract triangle pattern background"
      />

      <div class="past-events__img-wrapper">
        <img
          class="past-events__img"
          src="assets/styles/img/untitled1.png"
          alt="promotion for upcoming seminar"
        />
      </div>
    </section>
    <section class="about">
      <div class="about__img-wrapper">
        <img
          src="assets/styles/img/untitled2.png"
          alt="cinematic image of grappling"
        />
      </div>
    </section>
  </main>
</template>

<script>
import "assets/styles/css/main.css";
</script>

<style>
.app__main {
  background-color: var(--black_main);
  font-size: var(--f-size-base);
  min-height: 100%;
}

.app__header {
  background-color: var(--white_main);
}

.app__header h1 {
  font-size: var(--f-size-1);
}

.featured {
  padding: 0 var(--f-size-3) var(--f-size-3) var(--f-size-3);
}

.featured__heading {
  color: var(--white_main);
  padding: var(--f-size-3);
  text-align: center;
}

.featured__body {
  display: flex;
  align-items: center;
  gap: var(--f-size-base);
}

.featured__content {
  background-color: var(--white_main);
  color: #333;
  padding: var(--f-size-base);
  border-radius: var(--f-size-base);
  max-width: 50%;
}

.featured__content h3 {
  margin-bottom: calc(var(--f-size-base) / 2);
}

.featured__img-wrapper {
  max-width: 640px;
}

.featured__img {
  object-fit: contain;
}

/* utility */
.center {
  margin-left: auto;
  margin-right: auto;
}

.fill-container {
  width: 100%;
}
</style>
