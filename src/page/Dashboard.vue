<template>
  <div
    class="w-screen min-h-screen bg-black flex flex-row-reverse fixed top-0 left-0"
  >
    <div class="w-full bg-[#108798] h-20 flex justify-end items-center px-5">
      <div class="w-10 h-10 rounded-full bg-orange-400 cursor-pointer"></div>
    </div>
    <div
      class="w-60 h-screen bg-[#5C74D3] flex flex-col gap-8 py-8 text-white font-bold text-lg"
    >
      <h2 class="w-full uppercase text-center font-bold text-xl py-4">menu</h2>
      <ul class="uppercase flex flex-col gap-8">
        <li class="px-5 border border-solid border-[#5C74D3] cursor-pointer">
          show users
        </li>
        <li class="px-5 cursor-pointer">reports</li>
        <li class="px-5 cursor-pointer">rules</li>
      </ul>
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped></style>
