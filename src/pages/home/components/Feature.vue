<script setup lang="ts">
import Img from "../img/img.png";
</script>

<template>
  <!-- Container for demo purpose -->
  <div class="container my-24 mx-auto px-6">
    <!-- Section: Design Block -->
    <section class="mb-32">
      <div class="flex flex-wrap">
        <div class="mb-12 w-full shrink-0 grow-0 basis-auto lg:mb-0 lg:w-5/12">
          <div class="flex lg:py-12">
            <!-- Replace with an actual image of the Beijing-Hangzhou Grand Canal -->
            <img
              id="cta-img-nml-50" :src="Img"
              class="w-full rounded-lg shadow-lg" style="z-index: 1" alt="京杭大运河"
            >
          </div>
        </div>

        <div class="w-full shrink-0 grow-0 basis-auto lg:w-7/12">
          <div class="flex h-full items-center rounded-lg bg-yellow-500 p-6 text-center text-white lg:pl-12 lg:text-left">
            <div class="lg:pl-12">
              <h2 class="mb-6 text-3xl font-bold">
                京杭大运河：流动的历史
              </h2>
              <p class="mb-6 pb-2 lg:pb-0">
                京杭大运河，世界上里程最长、工程最大的古代运河，见证了中国古代劳动人民的智慧与勤劳。它不仅是交通要道，更是文化交流的纽带，促进了南北经济与文化的繁荣发展。
              </p>

              <div class="mx-auto mb-6 flex flex-col md:flex-row md:justify-around xl:justify-start">
                <p class="mx-auto mb-4 flex items-center md:mx-0 md:mb-2 lg:mb-0 xl:mr-20">
                  <!-- Replace with an SVG icon related to the Grand Canal, if available -->
                  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" class="mr-2 h-4 w-4">
                    <path
                      fill="currentColor"
                      d="M504 256c0 136.967-111.033 248-248 248S8 392.967 8 256 119.033 8 256 8s248 111.033 248 248zM227.314 387.314l184-184c6.248-6.248 6.248-16.379 0-22.627l-22.627-22.627c-6.248-6.249-16.379-6.249-22.628 0L216 308.118l-70.059-70.059c-6.248-6.248-16.379-6.248-22.628 0l-22.627 22.627c-6.248 6.248-6.248 16.379 0 22.627l104 104c6.249 6.249 16.379 6.249 22.628.001z"
                    />
                  </svg>
                  文化交流
                </p>

                <p class="mx-auto mb-4 flex items-center md:mx-0 md:mb-2 lg:mb-0 xl:mr-20">
                  <!-- Replace with an SVG icon related to the Grand Canal, if available -->
                  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" class="mr-2 h-4 w-4">
                    <path
                      fill="currentColor"
                      d="M504 256c0 136.967-111.033 248-248 248S8 392.967 8 256 119.033 8 256 8s248 111.033 248 248zM227.314 387.314l184-184c6.248-6.248 6.248-16.379 0-22.627l-22.627-22.627c-6.248-6.249-16.379-6.249-22.628 0L216 308.118l-70.059-70.059c-6.248-6.248-16.379-6.248-22.628 0l-22.627 22.627c-6.248 6.248-6.248 16.379 0 22.627l104 104c6.249 6.249 16.379 6.249 22.628.001z"
                    />
                  </svg>
                  经济发展
                </p>

                <p class="mx-auto mb-2 flex items-center md:mx-0 lg:mb-0">
                  <!-- Replace with an SVG icon related to the Grand Canal, if available -->
                  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" class="mr-2 h-4 w-4">
                    <path
                      fill="currentColor"
                      d="M504 256c0 136.967-111.033 248-248 248S8 392.967 8 256 119.033 8 256 8s248 111.033 248 248zM227.314 387.314l184-184c6.248-6.248 6.248-16.379 0-22.627l-22.627-22.627c-6.248-6.249-16.379-6.249-22.628 0L216 308.118l-70.059-70.059c-6.248-6.248-16.379-6.248-22.628 0l-22.627 22.627c-6.248 6.248-6.248 16.379 0 22.627l104 104c6.249 6.249 16.379 6.249 22.628.001z"
                    />
                  </svg>
                  历史遗产
                </p>
              </div>

              <p>
                京杭大运河作为世界文化遗产，不仅承载着丰富的历史故事，也是现代旅游和文化研究的重要资源。它的历史价值和现代意义，使得这条古老的运河在新时代焕发出新的活力。
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
  <!-- Container for demo purpose -->
</template>

<style scoped>
@media (min-width: 992px) {
  #cta-img-nml-50 {
    margin-left: 50px;
  }
}
</style>
