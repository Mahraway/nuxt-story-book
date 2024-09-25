<script setup lang="ts">
defineProps({
  str: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div>
    <h1>{{ str }}</h1>
  </div>
</template>

<style scoped>

</style>