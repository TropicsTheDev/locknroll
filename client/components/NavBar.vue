<template>
  <nav class="nav-bar">
    <h1>LOCK N' ROLL PROMOTIONS</h1>
    <ul class="nav-bar__content">
      <NavItem v-for="link in links" :navLink="link" />
    </ul>
  </nav>
</template>

<script setup>
const links = [
  {
    href: "gjgj",
    text: "Home",
  },
  {
    href: "bhj",
    text: "Buy Tickets",
  },
  {
    href: "bjkb",
    text: "Upcoming Seminars",
  },
  {
    href: "kjhk",
    text: "Contact",
  },
];
</script>

<style scoped>
.nav-bar {
  background-color: var(--white_main);
}

.nav-bar__content {
  list-style-type: none;
  padding: 0px;
  margin: 0px;
  overflow: hidden;
}
</style>
