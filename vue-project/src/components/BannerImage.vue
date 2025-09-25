<script lang="ts" setup>
import paperballots from '../assets/paperballots.jpg.avif'
</script>

<template>
  <div>
    <img :src="paperballots" alt="Paper Ballots" class="w-full h-96 object-cover" />

    <div
      class="absolute top-1/3 left-10 w-1/3 h-1/3 bg-[#487DB8] bg-opacity-70 -mt-25 flex items-center justify-center p-4 rounded-xl shadow-lg"
    >
      <h1 class="text-white text-xl font-bold flex items-start font-sans">
        Wat moet je weten voor het stemmen?
      </h1>
    </div>
  </div>
</template>
