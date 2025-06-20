<template>
<Header 
  title="Mind——图床" 
  desc="更多软件-<a 
    href='https://bbs.mostmind.top'  
    style='color: #1890ff; text-decoration: underline; cursor: pointer;' 
    target='_blank' 
    rel='noopener noreferrer'
  >点我</a>" 
/>  
  <main><RouterView /></main>
  <Footer />
  <Toaster />
</template>
<script setup lang="ts">
import Header from '@/components/Header/Header.vue';
import Footer from '@/components/Footer/Footer.vue';
import { Toaster } from '@/components/ui/toast';
</script>

<style scoped></style>
