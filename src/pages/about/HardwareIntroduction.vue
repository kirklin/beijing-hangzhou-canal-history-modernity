<script setup lang="ts">
defineProps({
  title: String,
  imgSrc: Object,
});
</script>

<template>
  <div
    class="zoom relative overflow-hidden rounded-lg bg-cover bg-no-repeat shadow-lg"
    style="background-position: 50%;" data-mdb-ripple="true" data-mdb-ripple-color="dark"
  >
    <img
      :src="imgSrc"
      class="w-full align-middle transition duration-300 ease-linear"
    >
    <a href="#">
      <div
        class="absolute inset-0 h-full w-full overflow-hidden bg-fixed"
        style="background-color: rgba(0, 0, 0, 0.3)"
      >
        <div class="flex h-full items-end justify-start">
          <h5 class="m-6 text-lg font-bold text-white">{{ title }}</h5>
        </div>
      </div>
      <div class="hover-overlay">
        <div
          class="mask absolute inset-0 h-full w-full overflow-hidden bg-fixed opacity-0 transition duration-300 ease-in-out hover:opacity-100"
          style="background-color: rgba(253, 253, 253, 0.15)"
        />
      </div>
    </a>
  </div>
</template>

<style scoped>

</style>
