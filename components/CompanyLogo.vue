<script setup lang="ts">
defineProps<{
  imgLink: string;
}>();
</script>
<template>
  <div class="w-1/5 h-auto aspect-square mx-auto overflow-hidden rounded-full">
    <img
      class="object-cover w-full h-full object-center"
      :src="imgLink"
      alt="logo"
      draggable="false"
    />
  </div>
</template>
