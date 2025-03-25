<script setup>
import { RouterView } from 'vue-router'
import NavBar from '@/components/common/NavBar.vue'
</script>

<template>
  <NavBar />
  <div class="container">
    <RouterView />
  </div>
</template>

<style scoped></style>
