<template>
  <div class="w-screen min-h-screen bg-black grid place-items-center">
    <div class="flex flex-col gap-10">
      <h2 class="text-white font-bold text-7xl">Hello World</h2>
      <div class="flex gap-8 justify-center text-white font-semibold">
        <router-link to="/login" class="bg-emerald-500 rounded-md p-5"
          >Go to Login</router-link
        >
        <router-link to="/register" class="bg-emerald-500 rounded-md p-5"
          >Go to Register</router-link
        >
      </div>
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped>
p {
  display: flex;
  gap: 2rem;
}
</style>
