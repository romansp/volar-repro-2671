<script setup lang="ts">
defineProps<{
  text: string
}>()
</script>

<template>
  <button title="Button Title">
    {{ text }}
  </button>
</template>
