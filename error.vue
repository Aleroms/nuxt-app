<template>
  <div class="mt-7 m-md bg-whitee shadow-md h-full">
    <p class="mt-7 text-7xl font-bold">{{ error.statusCode }}</p>
    <p class="mt-7 text-6xl">oops.</p>
    <p class="mt-7">{{ error.message }}</p>
  </div>
</template>

<script setup>
defineProps(["error"]);
</script>

<style scoped></style>
