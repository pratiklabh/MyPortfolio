<script setup>
const props = defineProps({
  text: String
});
</script>

<template>
  <p>{{ text }}</p>
</template>

<style scoped>
p {
  font-size: 1.2rem;
}
</style>
