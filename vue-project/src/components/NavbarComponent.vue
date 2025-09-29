<template>
  <nav class="flex flex-row w-full justify-between h-16 fixed z-50 bg-white">
    <div id="nav-logo">
      <p class="text-[24px] ml-5 mt-4 font-black">KIES<span class="italic font-normal">INZICHT</span></p>
    </div>

    <div class="flex justify-end items-center mt-2">
      <ul class="flex flex-row justify-end gap-x-10 -mr-130 text-[15px] font-medium cursor-pointer">
        <li class="hover:bg-gray-200">STEMWIJZER</li>
        <li>PARTIJEN</li>
        <li>FORUM</li>
        <li>UITSLAGEN</li>
      </ul>
    </div>

    <!--This is for the account part of the page-->
    <div class="flex justify-end mr-5 items-center mt-1">
      <p class="bg-[#27568B] text-white px-7 py-[7px] rounded-[15px] text-[15px] cursor-pointer hover:bg-[#2d4157]">INLOGGEN</p>
    </div>
  </nav>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100..900;1,100..900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Rubik:ital,wght@0,300..900;1,300..900&display=swap');

#nav-logo {
  font-family: 'Roboto', sans-serif;
}

ul {
  font-family: 'Rubik', sans-serif;
}
</style>
