<script setup lang="ts">
import ThemeChange from "./components/ThemeChange/index.vue";
import LocalesChange from "./components/LocalesChange/index.vue";

defineOptions({
  name: "Navbar",
});
const router = useRouter();
const go = (routerName: string) => {
  router.push(routerName);
};
</script>

<template>
  <div
    class="sticky top-0 z-30 flex h-16 w-full justify-center text-base-content opacity-90 backdrop-blur transition-all duration-100"
  >
    <div class="navbar bg-base-100">
      <div class="navbar-start">
        <div class="dropdown">
          <label tabindex="0" class="btn-ghost btn lg:hidden">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h8m-8 6h16" /></svg>
          </label>
          <ul tabindex="0" class="dropdown-content menu rounded-box menu-compact mt-3 w-52 bg-base-100 p-2 shadow">
            <li @click="go('about')">
              <a>关于</a>
            </li>
            <li @click="go('Sightseeing')">
              <a>观光</a>
            </li>
            <li @click="go('contact')">
              <a>联系我们</a>
            </li>
          </ul>
        </div>
        <a class="btn-ghost btn text-xl normal-case" @click="go('/')">京杭大运河</a>
      </div>
      <div class="navbar-center hidden lg:flex">
        <ul class="menu menu-horizontal px-1">
          <li @click="go('about')">
            <a>关于</a>
          </li>
          <li @click="go('Sightseeing')">
            <a>观光</a>
          </li>
          <li @click="go('contact')">
            <a>联系我们</a>
          </li>
        </ul>
      </div>
      <div class="navbar-end">
        <div>
          <ThemeChange />
          <LocalesChange />
          <span
            class="tooltip tooltip-bottom before:text-xs before:content-[attr(data-tip)]"
            data-tip="GitHub"
          >
          <span class="flex-none items-center">
            <a
              aria-label="Github"
              target="_blank"
              href="https://github.com/kirklin/beijing-hangzhou-canal-history-modernity"
              class="drawer-button normal-case btn btn-square btn-ghost"
            >
              <UnoCSSIconButton icon="i-mdi-github" />
            </a>
          </span>
        </span>
        </div>
      </div>
    </div>
  </div>
</template>
