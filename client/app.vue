<template>
  <main class="app__main">
    <header class="app__header">
      <h1>Lock N' Roll Promotions</h1>
      <NavBar />
    </header>
    <section class="featured">
      <h2 class="featured__heading">Featured Event</h2>
      <main class="featured__body">
        <article class="featured__content">
          <h3>Jason Valle</h3>
          <h4>No-Gi Jiu-Jitsu Seminar</h4>
          <p>
            Jason Valle's No-Gi Jiu Jitsu Seminar offers a comprehensive
            exploration of guard passing, leg lock entanglements, and
            transitioning to advantageous positions. Renowned for his expertise,
            Valle guides participants through breaking through defensive guards,
            mastering leg lock dynamics, and smoothly disengaging from
            entanglements. The seminar promises a nuanced understanding of these
            techniques, enhancing participants' grappling skills and strategic
            insights for effective maneuvering in the world of No-Gi Jiu Jitsu.
          </p>
          <a
            class="button center bold-font buy-ticket"
            href="https://www.eventbee.com/v/jason-valle-seminar#/tickets"
            target="_blank"
            >Buy Ticket</a
          >
        </article>
        <aside class="featured__img-wrapper">
          <img
            class="featured__img fill-container"
            src="assets/img/JasonPoster_Final.jpeg"
            alt="promotion for upcoming seminar"
          />
        </aside>
      </main>
    </section>
    <section class="past-events">
      <h2 class="past-events__heading">Past Events</h2>
      <main class="past-events__body">
        <aside class="past-events__img-wrapper">
          <img
            class="past-events__img fill-container"
            src="assets/img/untitled1.png"
            alt="cinematic picture of grappling"
          />
        </aside>
        <article class="past-events__content">
          <h3>Dante My Beloved</h3>
          <h4>No-Gi Jiu Jitsu Seminar</h4>
          <p>
            Lorem ipsum I love Dante Leon, consectetur adipiscing elit. Maecenas
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
      </main>
    </section>
    <section class="about">
      <div class="about__img-wrapper"></div>
    </section>
  </main>
</template>

<script>
import "assets/styles/main.css";
</script>

<style>
.app__main {
  background-color: var(--color_black);
  font-size: var(--f-size-base);
  min-height: 100%;
}

.app__header {
  color: var(--color_white);
  padding: var(--f-size-6);
  padding-bottom: 0;
}

.app__header h1 {
  font-size: var(--f-size-1);
  color: var(--color_white);
}

.featured__heading,
.past-events__heading {
  /* Font color and aligning headings to center */
  color: var(--white_main);
  padding: var(--f-size-3);
  text-align: center;
}

.featured__body,
.past-events__body {
  /* Centering */
  display: flex;
  align-items: center;
  gap: var(--f-size-base);
}

.featured__content,
.past-events__content {
  /* Setting text requirements */
  color: var(--white_main);
  padding: var(--f-size-base);
  border-radius: var(--f-size-base);
  max-width: 50%;
}

.featured__content h3,
.past-events__content h3 {
  /* Spacing between texts */
  margin-bottom: calc(var(--f-size-base) / 2);
}

.featured__img-wrapper,
.past-events__img-wrapper {
  /* Setting limitations on image size */
  max-width: 640px;
}

.featured__img,
.past-events__img {
  object-fit: contain;
}

.featured {
  /* Adding background image */
  background-image: url("assets/img/background2.jpg");
  background-size: cover;
  background-attachment: fixed;
  padding: 0 var(--f-size-3) var(--f-size-3) var(--f-size-3);
}

.buy-ticket {
  font-size: var(--f-size-6);
}

.past-events {
  background: radial-gradient(#333, #000 95%);
  background-repeat: no-repeat;
  padding: 0 var(--f-size-3) var(--f-size-3) var(--f-size-3);
}

.past-events__content {
  padding-left: auto;
}

/* utility */
.center {
  margin-left: auto;
  margin-right: auto;
}

.bold-font {
  font-weight: bold;
}

.fill-container {
  width: 100%;
}
</style>
