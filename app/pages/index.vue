<template>
  <main class="flex flex-col justify-center items-center h-screen">
    <p>리다이렉트 중...</p>
  </main>
</template>

<script setup>
import { onMounted } from 'vue';
definePageMeta({
  layout: 'custom'
});
  
onMounted(() => {
  window.location.href = 'https://shimaenaga.dev';
});
</script>
