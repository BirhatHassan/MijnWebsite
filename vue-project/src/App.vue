<script setup lang="ts">
  import NavBar from './components/NavbarComponent.vue';
  import heroimage from './components/HeroComponent.vue';
  import FooterComponent from './components/FooterComponent.vue';
</script>

<template>
  <header>
    <NavBar />
  </header>

  <main>
    <heroimage />
  </main>

  <footer>
    <FooterComponent />
  </footer>
</template>

<style scoped>
</style>
