<script setup lang="ts">
defineProps<{
    label: string
}>()
</script>
<template>
    <div class="">
        <div class="text-gray-700">{{ label }}</div>
        <div class="font-semibold"><slot /></div>
    </div>
</template>