<script setup lang="ts">
import Hero from "./components/Hero.vue";
import Stats from "./components/Stats.vue";
import Feature from "./components/Feature.vue";

defineOptions({
  name: "Home",
});
</script>

<template>
  <Hero />
  <Stats />
  <Feature />
</template>

<style scoped></style>
