<script setup lang="ts">
import Avatar from "~/assets/avatar.jpg";

defineOptions({
  name: "LayoutFooter",
});
</script>

<template>
  <footer
    class="sticky bottom-0 border-t border-base-100 bg-base-200 px-4 pt-2 text-base-content opacity-90 footer footer-center z-30"
  >
    <div class="max-w-6xl w-full flex flex-row items-center justify-between gap-6">
      <a
        href="https://github.com/kirklin"
        target="_blank"
        rel="nofollow"
        class="inline-flex items-center justify-center hover:opacity-90"
      ><div class="mr-3 avatar">
         <div class="h-14 w-14 bg-neutral p-px mask mask-squircle">
           <img
             width="54"
             height="54"
             :src="Avatar"
             alt="Kirk Lin"
             class="mask mask-squircle"
           >
         </div>
       </div>
        <div class="text-left">
          <p class="text-xs text-base-content text-opacity-50">Created by</p>
          <h2 class="text-lg text-base-content font-bold">Kirk Lin</h2>
        </div>
      </a>
      <div class="flex flex-col items-center gap-4 text-left sm:flex-row">
        <div class="flex gap-4 pb-4">
          <a
            href="https://github.com/kirklin/beijing-hangzhou-canal-history-modernity"
            target="_blank"
            rel="nofollow"
            class="w-[130px] flex flex-col items-center rounded bg-base-100"
          >
            <h3 class="p-2 text-xs text-base-content/50 font-bold">beijing-hangzhou-canal-history-modernity™</h3>
            <p class="px-1.5 py-2 text-xs text-base-content/50 tracking-tighter">
              All Rights Reserved.
            </p>
          </a>
        </div>
      </div>
    </div>
  </footer>
</template>
