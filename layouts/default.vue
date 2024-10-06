<template>
  <div class="flex flex-col h-screen">
    <Header />
    <div class="flex-grow flex">
      <Sidebar />
      <Main />
    </div>
    <Footer />
  </div>
</template>

<script setup>
import Header from '@/components/Header.vue';
import Sidebar from '@/components/Sidebar.vue';
import Main from '@/components/Main.vue';
import Footer from '@/components/Footer.vue';
</script>
