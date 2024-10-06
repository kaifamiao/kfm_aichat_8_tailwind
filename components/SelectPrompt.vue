<template>
  <select>
    <option v-for="option in options" :key="option">{{ option }}</option>
  </select>
</template>

<script setup>
const options = ['Option 1', 'Option 2', 'Option 3'];
</script>
