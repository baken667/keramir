<script setup lang="ts">
defineProps<{
  link: string;
}>();
</script>
<template>
  <a :href="link" target="_blank">
    <slot />
  </a>
</template>
