<template>
  <!-- div for both contact fillout form and contact information -->
  <main class="contact__main">
    <section class="contact__body">
      <h2 class="contact__heading">Contact Us</h2>
      <!-- div for contact info to reach us -->
      <section class="contact__info">
        <div class="contact__info-ig">
          <a href="https://www.instagram.com/locknroll.promotions"><img class="icon__email" src="assets/img/icons8-instagram-188.png"></a>
          <h5>@LOCKNROLL.PROMOTIONS</h5>
        </div>
        <div class="contact__info-fb">
          <a href="https://www.facebook.com/locknroll.promotions"><img class="icon__email" src="assets/img/icons8-facebook-188.png"></a>
          <h5>@LOCKNROLL.PROMOTIONS</h5>
        </div>
        <div class="contact__info-email">
          <a href="mailto:locknroll.promotions@gmail.com"><img class="icon__email" src="assets/img/icons8-gmail-188.png"></a>
          <h5>LOCKNROLL.PROMOTIONS@GMAIL</h5>
        </div>
      </section>

    </section>
  </main>
</template>

<style>
.contact__main {
  background: radial-gradient(#333 30%, #000);
  background: fill;
  background-attachment: fixed;
}

.contact__heading {
  text-align: center;
  padding: var(--f-size-3);
}

.contact__info {
  min-height: 100vh;
  text-align: center;
  display: flex;
  padding-top: 250px;
  box-sizing: border-box;
  justify-content: space-evenly;
}

.contact__info-ig,
.contact__info-fb,
.contact__info-email{
  display: flex;
  flex-direction: column;
}
</style>