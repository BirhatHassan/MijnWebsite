<template>
  <div id="hero-section" class="relative h-[700px] overflow-hidden">
    <img src="../assets/stemhokje.jpg" alt="Hero Image" class="w-full h-full mt-3 brightness-40 object-cover" />
    <div class="absolute top-50 left-20 flex flex-col max-w-[600px]">
      <h1 class="text-white text-[48px] font-black">
        Hoe telt jouw stem mee?
      </h1>
      <p class="text-white text-lg leading-relaxed mt-4 max-w-[441px]">
        Op <span class="text-[#72A3D9]">KiesInzicht</span> ontdek je hoe stemmen werken, vorm je je eigen mening en lees je alles over de afgelopen verkiezingen.
      </p>
      <div class="text-[21px] flex flex-row gap-x-4 text-white mt-5 flex-nowrap">
        <p class="px-6 py-3 bg-[#27568B] text-white rounded-[15px] cursor-pointer hover:bg-[#2d4157]">
          Bekijk de verkiezingsuitslagen
        </p>
        <p class="px-6 py-3 bg-white rounded-[15px] text-[#27568B] cursor-pointer hover:bg-gray-200">
          Ga naar het forum
        </p>
      </div>
  </div>
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Rubik:ital,wght@0,300..900;1,300..900&display=swap');

#hero-section {
  font-family: 'Rubik', sans-serif;
}
</style>
