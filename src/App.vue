<template>
  <nav class="navbar w-full bg-base-200">
    <div class="flex flex-1 md:gap-1 lg:gap-2">
      <span class="tooltip tooltip-bottom before:text-xs before:content-[attr(data-tip)]" data-tip="Menu"
        ><label for="drawer" class="btn btn-square btn-ghost drawer-button lg:hidden"
          ><svg width="20" height="20" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" class="inline-block h-5 w-5 stroke-current md:h-6 md:w-6"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path></svg></label
      ></span>
      <div class="flex items-center gap-2">
        <a href="/" aria-current="page" aria-label="Homepage" class="flex-0 btn btn-ghost px-2"
          ><div class="font-title text-primary inline-flex text-lg transition-all duration-200 md:text-3xl"><span class="text-accent">&lt;Learning /&gt;</span></div></a
        >
      </div>
    </div>
    <ChangeTheme />
  </nav>
  <div class="drawer drawer-mobile bg-base-200">
    <input id="drawer" type="checkbox" class="drawer-toggle" />
    <div class="drawer-content flex flex-col items-center justify-center bg-base-100">
      <!-- Page content here -->
      <RouterView />
    </div>
    <div class="drawer-side">
      <label for="my-drawer-2" class="drawer-overlay"></label>
      <ul class="menu p-4 w-80 bg-base-200 text-base-content">
        <!-- Sidebar content here -->
        <li><a>Sidebar Item 1</a></li>
        <li><a>Sidebar Item 2</a></li>
      </ul>
    </div>
  </div>
</template>

<script setup>
import ChangeTheme from './components/ChangeTheme.vue';
</script>
