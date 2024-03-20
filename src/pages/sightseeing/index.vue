<script setup lang="ts">
import img00 from "./img/img.png";
import img1 from "./img/img_1.png";
import img2 from "./img/img_2.png";
</script>

<template>
  <header class="mx-auto box-content max-w-screen-2xl px-5 pt-[60px] sm:pt-[100px] md:px-[50px]">
    <h1 class="max-w-[80%] font-song text-[120px]">
      京杭大运河观光之旅
    </h1>
    <p class="mt-[30px] max-w-[80%] font-italics text-2xl font-bold ">
      <span class="false">
        京杭大运河，这条古老的水上丝绸之路，见证了中国古代劳动人民的智慧与勤劳，是连接历史与现代的文化纽带。<br>
        沿着这条历史悠久的运河，您可以探索丰富的文化遗产，感受古今交融的韵味。
      </span>
    </p>
  </header>
  <div class="container my-24 mx-auto px-6">
    <!-- Section: Design Block -->
    <section class="mb-32 ">
      <div class="mb-12 flex flex-wrap">
        <div class="mb-6 w-full shrink-0 grow-0 basis-auto lg:mb-0 lg:w-6/12 lg:pr-6">
          <div
            class="ripple relative overflow-hidden rounded-lg bg-cover bg-no-repeat shadow-lg"
            style="background-position: 50%" data-mdb-ripple="true" data-mdb-ripple-color="light"
          >
            <!-- Replace with an actual image of the Beijing-Hangzhou Grand Canal -->
            <img :src="img00" class="w-full" alt="京杭大运河">
            <a href="#!">
              <div
                class="absolute inset-0 h-full w-full overflow-hidden bg-fixed opacity-0 transition duration-300 ease-in-out hover:opacity-100"
                style="background-color: rgba(251, 251, 251, 0.2)"
              />
            </a>
          </div>
        </div>

        <div class="w-full shrink-0 grow-0 basis-auto lg:w-6/12 lg:pl-6">
          <h3 class="mb-4 text-2xl font-bold">
            历史与现代的交融
          </h3>
          <div class="mb-10 flex items-center text-sm font-medium text-red-600">
            <!-- Replace with an appropriate icon from Font Awesome or another source -->
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 496 512" class="mr-2 h-4 w-4">
              <!-- SVG content for illustration -->
            </svg>
            沿着运河追溯历史
          </div>
          <div class="font-italics text-base-content">
            <p class="mb-6">
              京杭大运河不仅是一条水道，它还是中国历史的缩影。沿途的古迹、桥梁、古镇都诉说着千年的故事。
            </p>
            <p class="mb-6">
              游客可以乘坐游船，穿梭于古老的运河之上，体验古代商旅的旅程，同时欣赏沿岸的现代城市风光。
            </p>
            <p class="">
              每一站都有不同的风景和故事，从杭州的西湖到北京的颐和园，每一处都是历史的见证。
            </p>
          </div>
        </div>
      </div>

      <div class="mb-12 flex flex-wrap lg:flex-row-reverse">
        <div class="mb-6 w-full shrink-0 grow-0 basis-auto lg:mb-0 lg:w-6/12 lg:pl-6">
          <div
            class="ripple relative overflow-hidden rounded-lg bg-cover bg-no-repeat shadow-lg"
            style="background-position: 50%" data-mdb-ripple="true" data-mdb-ripple-color="light"
          >
            <!-- Replace with an actual image showcasing the Grand Canal's cultural significance -->
            <img :src="img1" class="w-full" alt="京杭大运河文化">
          </div>
        </div>

        <div class="w-full shrink-0 grow-0 basis-auto lg:w-6/12 lg:pr-6">
          <h3 class="mb-4 text-2xl font-bold">
            运河文化：千年的传承与保护
          </h3>
          <div class="mb-10 flex items-center text-sm font-medium text-blue-600">
            <!-- Replace with an appropriate icon from Font Awesome or another source -->
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" class="mr-2 h-4 w-4">
              <!-- SVG content for illustration -->
            </svg>
            探索运河的文化遗产
          </div>
          <div class="font-italics text-base-content">
            <p class="mb-6">
              京杭大运河沿线分布着众多文化遗产，如扬州的瘦西湖、苏州的运河古镇等，每一处都是中国传统文化的瑰宝。
            </p>
            <p class="mb-6">
              运河两岸的古建筑、石桥、水闸等遗迹，不仅展现了古代水利工程的伟大，也见证了中国古代的经济和社会发展。
            </p>
            <p class="">
              通过保护和修复这些文化遗产，京杭大运河成为了连接过去与未来的桥梁，让游客在游览的同时，也能感受到历史的厚重和文化的韵味。
            </p>
          </div>
        </div>
      </div>

      <div class="flex flex-wrap">
        <div class="mb-6 w-full shrink-0 grow-0 basis-auto lg:mb-0 lg:w-6/12 lg:pr-6">
          <div
            class="ripple relative overflow-hidden rounded-lg bg-cover bg-no-repeat shadow-lg"
            style="background-position: 50%" data-mdb-ripple="true" data-mdb-ripple-color="light"
          >
            <!-- Replace with an actual image showcasing the natural beauty along the Grand Canal -->
            <img :src="img2" class="w-full" alt="京杭大运河自然风光">
          </div>
        </div>

        <div class="w-full shrink-0 grow-0 basis-auto lg:w-6/12 lg:pl-6">
          <h3 class="mb-4 text-2xl font-bold">
            运河风光：自然与人文的和谐
          </h3>
          <div class="mb-10 flex items-center text-sm font-medium text-yellow-600">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" class="mr-2 h-4 w-4">
              <!-- SVG content for illustration -->
            </svg>
            享受运河的自然美景
          </div>
          <div class="font-italics text-base-content">
            <p class="mb-6">
              京杭大运河两岸绿树成荫，四季花开，是自然美景与人文景观的完美结合。在这里，您可以感受到与自然和谐共存的宁静与美好。
            </p>
            <p class="mb-6">
              无论是春天的桃红柳绿，夏日的荷花盛开，秋天的金黄稻田，还是冬日的雪景如画，运河的每个季节都有独特的风貌。
            </p>
            <p class="">
              沿着运河散步或骑行，您可以近距离感受这份自然之美，体验中国古代诗人笔下的江南水乡风情。
            </p>
          </div>
        </div>
      </div>
    </section>
    <!-- Section: Design Block -->
  </div>
</template>

<style scoped>
</style>
