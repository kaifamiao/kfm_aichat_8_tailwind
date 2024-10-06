<template>
  <div class="flex-grow overflow-auto">
    <!-- 这里会显示聊天内容 -->
    <Chat v-if="isNewChat" />
    <HistoryChat v-else />
  </div>
</template>

<script setup>
import Chat from './Chat.vue';
import HistoryChat from './HistoryChat.vue';

const isNewChat = true;
</script>
