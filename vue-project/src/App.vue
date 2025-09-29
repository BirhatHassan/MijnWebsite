<script setup lang="ts">
  import NavBar from './components/NavbarComponent.vue';
  import heroimage from './components/HeroComponent.vue';
  import FooterComponent from './components/FooterComponent.vue';
import ContentComponent from './components/ContentComponent.vue';
</script>

<template>
  <header>
    <NavBar />
  </header>

  <main>
    <heroimage />
    <ContentComponent />
  </main>

  <footer>
    <FooterComponent />
  </footer>
</template>

<style scoped>
</style>
