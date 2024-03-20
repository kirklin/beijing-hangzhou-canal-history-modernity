<script setup lang="ts">
import img00 from "./img/img.png";
import img1 from "./img/img_1.png";
import img2 from "./img/img_2.png";
import img3 from "./img/img_3.png";
import img4 from "./img/img_4.png";
import img5 from "./img/img_5.png";
import img6 from "./img/img_6.png";
import img7 from "./img/img_7.png";
import main from "./img/main.png";
import img8 from "./img/img_8.png";
import HardwareIntroduction from "./HardwareIntroduction.vue";
</script>

<template>
  <div class="mt-[60px] mb-[80px]">
    <div class="w-full px-[40px] md:px-[50px]">
      <div class="mx-auto max-w-screen-2xl">
        <div class="py-[45px]">
          <h1 class="text-center font-song text-5xl">
            京杭大运河简介
          </h1>
          <div class="mx-auto mt-2 h-[5px] w-12 bg-black" />
        </div>
        <h2 class="my-5 text-center font-song text-7xl font-bold">
          京杭大运河，连接历史与现代的水上丝绸之路。
        </h2>
      </div>
    </div>
    <!-- Container for demo purpose -->
    <div class="container my-24 mx-auto px-6 font-song">
      <!-- Section: Design Block -->
      <section class="mb-32 ">
        <!-- Replace with an actual image of the Beijing-Hangzhou Grand Canal -->
        <img :src="main" class="mb-6 w-full rounded-lg shadow-lg" alt="京杭大运河">

        <div class="mb-6 flex items-center">
          <!-- Placeholder for author and publish date -->
        </div>

        <h1 class="mb-6 text-4xl font-bold">
          京杭大运河的历史与文化
        </h1>

        <p class="mb-6 text-xl">
          京杭大运河，始建于公元前486年，是世界上最长的古代运河，也是中国古代三项伟大工程之一。它不仅促进了南北经济文化的交流，更是中国古代劳动人民智慧的结晶。运河全长约1794公里，流经浙江、江苏、山东、河北四省及天津、北京两市，贯通五大水系，至今仍在使用，是中国文化地位的象征之一。
        </p>
        <h1 class="mb-6 text-4xl font-bold">
          运河的现代价值与影响
        </h1>
        <div class="mb-6 grid gap-6 lg:grid-cols-2">
          <!-- Placeholder for images or descriptions of the canal's modern significance -->
        </div>
        <p class="mb-6 text-xl">
          京杭大运河不仅是历史的遗产，它在现代社会中依然扮演着重要角色。作为世界文化遗产，它吸引了无数游客，促进了沿线城市的旅游业发展。同时，运河的维护和利用也体现了现代工程技术的进步，对研究中国古代水利工程、经济发展和文化交流具有重要价值。
        </p>
        <h1 class="mb-6 text-4xl font-bold">
          保护与传承
        </h1>

        <p class="mb-6 text-xl">
          为了保护这一珍贵的文化遗产，中国政府和相关组织进行了一系列的修复和保护工作。通过科学研究和国际合作，京杭大运河的保护工作不断取得进展，确保这一历史遗迹能够传承给后世。
        </p>
        <!-- Container for demo purpose -->
        <div class="container my-24 mx-auto">
          <!-- Section: Design Block -->
          <section class="mb-32 text-gray-800">
            <h2 class="mb-12 text-center text-3xl font-bold">
              运河风光
            </h2>

            <div class="grid gap-6 lg:grid-cols-3">
              <HardwareIntroduction title="" :img-src="img00" />
              <HardwareIntroduction title="" :img-src="img2" />
              <HardwareIntroduction title="" :img-src="img1" />
              <HardwareIntroduction title="" :img-src="img3" />
              <HardwareIntroduction title="" :img-src="img4" />
              <HardwareIntroduction title="" :img-src="img5" />
              <HardwareIntroduction title="" :img-src="img6" />
              <HardwareIntroduction title="" :img-src="img7" />
              <HardwareIntroduction title="" :img-src="img8" />
            </div>
          </section>
        <!-- Section: Design Block -->
        </div>
      <!-- Container for demo purpose -->
      </section>
    <!-- Section: Design Block -->
    </div>
  </div>
</template>

<style scoped>
.zoom:hover img {
  transform: scale(1.1);
}
</style>
