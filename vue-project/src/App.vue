<script setup lang="ts">
import BannerImage from './components/BannerImage.vue';
import Footer from './components/Footer.vue';
import NavBar from './components/NavBar.vue'
</script>

<template>
  <header>
    <nav-bar />
  </header>

  <main>
    <BannerImage />
  </main>

  <footer>
    <Footer />
  </footer>
</template>

<style scoped>
</style>
