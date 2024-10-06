<template>
  <div class="flex justify-between items-center p-4 bg-gray-200">
    <button @click="$emit('toggle-sidebar')">Toggle Sidebar</button>
    <SelectModel />
    <SelectPrompt />
    <SelectKB />
  </div>
</template>

<script setup>
import SelectModel from './SelectModel.vue';
import SelectPrompt from './SelectPrompt.vue';
import SelectKB from './SelectKB.vue';
</script>
