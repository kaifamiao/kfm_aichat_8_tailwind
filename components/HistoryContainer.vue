<template>
  <div class="h-48 overflow-y-auto">
    <ChatList />
  </div>
</template>

<script setup>
import ChatList from './ChatList.vue';
</script>

<style scoped>
.history-container {
  height: calc(100vh - 200px); /* 动态调整高度 */
}
</style>
