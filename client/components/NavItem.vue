<template>
  <li class="nav-item">
    <a :href="navLink.href">{{ navLink.text }}</a>
  </li>
</template>

<script setup>
const props = defineProps(["navLink"]);
</script>

<style scoped>
.nav-item {
  display: inline-block;
}
.nav-item a {
  text-decoration: none;
  color: black;
  display: block;
  text-align: center;
  padding: 0.8em;
  transition: background-color 0.75s;
}
.nav-item a:hover {
  background-color: #e1dff6;
}
</style>
