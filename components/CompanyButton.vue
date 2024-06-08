<script setup lang="ts">
defineProps<{
  href: string;
}>();
</script>
<template>
  <a :href="href" target="_blank" class="block bg-purple-800 text-white px-4 py-2 rounded text-center font-semibold text-lg">
    <slot />
  </a>
</template>
