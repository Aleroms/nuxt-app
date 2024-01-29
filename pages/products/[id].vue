<template>
  <div>
    <p>Product details for {{ id }}</p>
  </div>
</template>

<script lang="ts" setup>
const { id } = useRoute().params;
definePageMeta({
  layout: "products",
});
</script>

<style></style>
