<script setup>
const props = defineProps({})
</script>

<template>
  <div class="alert alert-primary" role="alert">{{ props.children }}</div>
</template>
