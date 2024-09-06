<script setup>
const props = defineProps({
  text: String
});
</script>

<template>
  <h1>{{ text }}</h1>
</template>

<style scoped>
h1 {
  font-size: 2.5rem;
}
</style>
