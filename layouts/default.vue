<template>
  <header class="shadow-sm bg-white">
    <nav class="container mx-auto p-4 flex justify-between">
      <NuxtLink to="/" class="font-bold">Nuxt App</NuxtLink>
      <ul class="flex gap-4">
        <li><NuxtLink to="/">Home</NuxtLink></li>
        <li><NuxtLink to="/about">About</NuxtLink></li>
        <li><NuxtLink to="/products" class="bg-[#12b488] text-white px-3 py-2 rounded-md text-sm text-white;">Products</NuxtLink></li>
      </ul>
    </nav>
  </header>
  <!-- output the page content  -->
  <div class="container mx-auto p-4">
    <slot />
  </div>
</template>

<script lang="ts" setup></script>

<style>
.router-link-exact-active {
  color: #12b488;
}
</style>
