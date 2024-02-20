<template>
  <nav class="nav-bar center">
    <ul class="nav-bar__content">
      <NavItem v-for="(link, index) in links" :navLink="link" />
    </ul>
  </nav>
</template>

<script setup>
const links = [
  {
    href: "/",
    text: "Home",
  },
  // {
  //   href: "bhj",
  //   text: "Buy Tickets",
  // },
  // {
  //   href: "bjkb",
  //   text: "Upcoming Seminars",
  // },
  {
    href: "/contact",
    text: "Contact",
  },
];
</script>

<style scoped>
.nav-bar {
  background-color: inherit;
  font-size: var(--f-size-5);
}

.nav-bar__content {
  list-style-type: none;
  padding: 0px;
  margin: 0px;
  overflow: hidden;
  display: flex;
  justify-content: end;
}
</style>
