<template>
  <li class="nav-item" :class="{ 'nav-item--active': isActive }">
    <a :href="navLink.href">{{ navLink.text }}</a>
  </li>
</template>

<script setup>
const props = defineProps(["navLink"]);
const route = useRoute();

const isActive = computed(() => props.navLink.href === route.path);
</script>

<style scoped>
.nav-item {
  display: inline-block;
}
.nav-item a {
  text-decoration: none;
  color: inherit;
  display: block;
  text-align: center;
  padding: 0.8em;
  transition: background-color 0.75s;
}
.nav-item a:hover {
  background-color: #e1dff6;
}

.nav-item--active {
  background-color: var(--color_main);
}
</style>
