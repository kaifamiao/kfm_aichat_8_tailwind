<template>
  <main class="flex flex-col w-full">
    <MainHeader @toggle-sidebar="toggleSidebar" />
    <MainContent />
    <ChatInput />
  </main>
</template>

<script setup>
import MainHeader from './MainHeader.vue';
import MainContent from './MainContent.vue';
import ChatInput from './ChatInput.vue';

const toggleSidebar = () => {
  // 逻辑处理Sidebar显示隐藏
};
</script>
