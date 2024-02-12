<template>
  <main class="app__main">
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
    <section class="about-us">
      <h2 class="about-us__heading">About Us</h2>
      <main class="about-us__body">
        <article class="about-us__content center">
          <p>
            Lorem ipsum I love Dante Leon, consectetur adipiscing elit. Maecenas
            urna nibh, sagittis a scelerisque in, tempor mattis arcu.
            Pellentesque a auctor lacus. Integer lobortis molestie nulla in
            mattis. Maecenas faucibus mi vel orci aliquam vehicula. Vivamus
            pulvinar tempor mauris, ut vestibulum erat placerat sed.
          </p>
          <p>
            Mauris sit amet orci est. Donec condimentum ut nibh sed fringilla.
            Aliquam luctus ultricies semper. Mauris elementum, libero ac
            hendrerit molestie, sapien sem egestas dui, vel pharetra lectus odio
            id ex. Nam ultrices consequat luctus. Nulla auctor sem ut est
            dignissim, in accumsan sapien congue. In vel ultrices odio, sed
            facilisis augue.
          </p>
        </article>
      </main>
    </section>
  </main>
</template>

<style>
.app__main {
  background-color: var(--color_black);
  font-size: var(--f-size-base);
  min-height: 100%;
}

.featured {
  /* Adding background image */
  background-image: url("assets/img/background2.jpg");
  background-size: cover;
  background-attachment: fixed;
  padding: 0 var(--f-size-3) var(--f-size-3) var(--f-size-3);
}

.featured__heading,
.about-us__heading {
  /* Font color and aligning headings to center */
  color: var(--white_main);
  padding: var(--f-size-3);
  text-align: center;
}

.featured__body,
.about-us__body {
  /* Centering */
  display: flex;
  align-items: center;
  gap: var(--f-size-base);
}

.featured__content,
.about-us__content {
  /* Setting text requirements */
  color: var(--white_main);
  padding: var(--f-size-base);
  border-radius: var(--f-size-base);
  max-width: 50%;
}

.featured__content h3,
.about-us__content h3 {
  /* Spacing between texts */
  margin-bottom: calc(var(--f-size-base) / 2);
}

.featured__img-wrapper {
  /* Setting limitations on image size */
  max-width: 640px;
}

.featured__img {
  box-shadow: 0px 0px 25px black;
  object-fit: contain;
}

.about-us {
  background: radial-gradient(#333, #000 95%);
  background-repeat: no-repeat;
  box-shadow: 0 -10px 25px #0a0a0a;
  padding: 0 var(--f-size-3) var(--f-size-3) var(--f-size-3);
}

.about-us__content {
  text-align: center;
  width: 50ch;
  padding-top: 0;
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
