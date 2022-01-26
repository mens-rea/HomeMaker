<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>

<template>
  <h1>HomeMaker</h1>
  <p>Household management should be fun...</p>
</template>

<style scoped>
  /* Place your custom css here */
</style>
