<template>
  <aside v-if="isVisible" class="w-64 h-full bg-gray-700 text-white">
    <NewChat />
    <HistoryContainer />
    <Setting />
  </aside>
</template>

<script setup>
import NewChat from './NewChat.vue';
import HistoryContainer from './HistoryContainer.vue';
import Setting from './Setting.vue';

import { ref } from 'vue';
const isVisible = ref(true);
</script>

<style scoped>
@media (max-width: 768px) {
  aside {
    display: none;
  }
}
</style>
