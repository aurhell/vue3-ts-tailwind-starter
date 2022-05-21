<script setup lang="ts">
  import { RouterLink, RouterView } from 'vue-router'
  import HelloWorld from '@/components/HelloWorld.vue'
</script>

<template>
  <header class="flex flex-col text-center">
    <img
      alt="Vue logo"
      class="mx-auto mt-10"
      src="@/assets/logo.svg"
      width="125"
      height="125"
    />

    <HelloWorld msg="You did it!" />

    <nav>
      <!-- <RouterLink to="/">Home</RouterLink> -->
    </nav>
  </header>

  <RouterView />
</template>

<style></style>
