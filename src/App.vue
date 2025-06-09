<template>
  <Header title="ikun的图床" desc="卤出鸡脚了吧！树枝666，小黑子 苏珊，食不食油饼？" />
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
