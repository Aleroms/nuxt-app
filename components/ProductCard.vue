<template>
  <div class="p-3 rounded-md bg-whitee shadow-md h-full text-center">
    <img :src="product.image" alt="product thumb" class="thumb" />
    <p class="font-bold text-gray-500 m-4 truncate">{{ product.title }}</p>
    <NuxtLink :to="`/products/${product.id}`">
      <p
        class="my-4 bg-[#12b488] text-white px-3 py-2 rounded-md text-sm text-white"
      >
        View Details
      </p>
    </NuxtLink>
  </div>
</template>

<script setup>
const { product } = defineProps(["product"]);
</script>

<style scoped></style>
