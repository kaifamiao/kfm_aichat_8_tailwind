<template>
  <ul>
    <li v-for="chat in chats" :key="chat.id">{{ chat.name }}</li>
  </ul>
</template>

<script setup>
const chats = [
  { id: 1, name: 'Chat 1' },
  { id: 2, name: 'Chat 2' },
];
</script>
