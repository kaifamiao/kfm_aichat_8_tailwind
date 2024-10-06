<template>
  <button @click="showModal = true" class="p-2 bg-gray-800 w-full">Settings</button>
  <SettingModal v-if="showModal" @close="showModal = false" />
</template>

<script setup>
import { ref } from 'vue';
import SettingModal from './SettingModal.vue';

const showModal = ref(false);
</script>
