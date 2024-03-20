<script setup lang="ts">
import HeroImg from "../img/hero.png";
</script>

<template>
  <div class="hero min-h-screen mt-[-4rem]" :style="{'background-image': 'url('+HeroImg+')'}">
    <div class="px-6 py-12 text-center text-gray-800 md:px-12 lg:my-12 lg:text-left">
      <div class="container mx-auto xl:px-32">
        <div class="hero-overlay"></div>
        <div class="grid items-center gap-12 lg:grid-cols-2">
          <div class="mt-12 lg:mt-0" style="z-index: 100">
            <h1 class="mb-12 text-5xl font-bold tracking-tight md:text-6xl xl:text-7xl">
              探索京杭大运河的历史深度与文化价值 <br>
              <span class="text-blue-600">感受这条古老水道的现代魅力。</span>
            </h1>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.hero-overlay {
  /* 覆盖整个容器 */
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  /* 渐变背景从透明到不透明 */
  background: linear-gradient(to bottom, rgba(255, 255, 255, 0), white 90%);
  /* 确保文本内容在覆盖层之上 */
  z-index: 1;
}
/* 如果需要在黑色主题下使用，可以调整渐变的颜色 */
[data-theme='dark'] .hero-overlay {
  background: linear-gradient(to bottom, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.5) 60%);
}
</style>
