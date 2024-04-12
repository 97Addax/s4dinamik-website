<script setup>
import { RouterLink, RouterView } from 'vue-router';
</script>

<template>
  <div>
    <header class="fixed top-0 left-0 w-full bg-white py-4 px-10 flex justify-center border-b border-gray-200">
      <RouterLink to="/">
        <img src="@/assets/logo.svg" alt="s4dinamik" class="h-14">
      </RouterLink>
    </header>

    <div class="pt-[90px]">
      <RouterView />
    </div>
  </div>
</template>