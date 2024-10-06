<template>
  <div class="p-4 flex items-center">
    <SelectList />
    <textarea class="flex-grow ml-2" placeholder="Type a message..."></textarea>
    <button class="ml-2 bg-blue-500 p-2">Send</button>
  </div>
</template>

<script setup>
import SelectList from './SelectList.vue';
</script>
