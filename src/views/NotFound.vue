<script setup lang="ts">
import Logo from '@/assets/logo.svg'
import { RouterLink } from 'vue-router'
</script>

<template>
  <section
    class="flex flex-col justify-center items-center w-screen h-screen p-8 md:p-16 bg-background"
  >
    <div class="flex flex-col items-center">
      <img :src="Logo" class="h-40 md:h-52" />
      <h1 class="text-4xl md:text-6xl text-primary">BlogStack</h1>
    </div>
    <h1 class="text-red-600 text-xl md:text-3xl font-bold my-12">Error 404 | Page Not Found</h1>
    <RouterLink
      to="/dashboard"
      class="btn btn-wide btn-accent text-white text-lg md:text-xl my-12 text-primary"
    >
      Explore
    </RouterLink>
  </section>
</template>
