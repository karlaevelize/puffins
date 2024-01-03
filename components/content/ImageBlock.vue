<script setup lang="ts">
defineProps<{
  imageUrl: string;
}>();
</script>

<template>
  <div class="px-2 py-7">
    <img
      class="grayscale rounded-full aspect-square w-72 mx-auto"
      :src="imageUrl"
    />
  </div>
</template>
