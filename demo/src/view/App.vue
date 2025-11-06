<script setup lang="ts">
import Header from '@/components/Header.vue';
import Footer from '@/components/Footer.vue';
import DiscoverSection from '@/components/ui/DiscoverSection.vue';
import SugestionForm from '@/components/ui/SugestionForm.vue';
import { NLayout, NFlex } from 'naive-ui';
</script>

<template>
  <n-layout>
    <n-flex vertical justify="space-between">
      <Header />

      <n-layout has-sider>
        <DiscoverSection />
        <SugestionForm />
      </n-layout>

      <Footer/>
    </n-flex>
  </n-layout>
</template>

<style scoped></style>
