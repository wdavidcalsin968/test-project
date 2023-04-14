<template>
  <div class="grid place-items-center w-screen min-h-screen bg-black">
    <div
      class="border border-solid border-[#69AAE7] text-[#69AAE7] flex flex-col gap-3 p-11 w-96"
    >
      <h2 class="uppercase text-center font-semibold text-2xl">Register</h2>
      <form action="" class="flex flex-col gap-5">
        <label for="" class="flex flex-col"
          >Name
          <input
            type="text"
            class="bg-[#121212] border border-solid border-[#69AAE7] px-2 py-2 w-full"
          />
        </label>
        <label for="" class="flex flex-col"
          >Email
          <input
            type="text"
            class="bg-[#121212] border border-solid border-[#69AAE7] px-2 py-2 w-full"
          />
        </label>
        <label for="" class="flex flex-col"
          >User
          <input
            type="text"
            class="bg-[#121212] border border-solid border-[#69AAE7] px-2 py-2 w-full"
          />
        </label>
        <label for="" class="flex flex-col"
          >Password
          <input
            type="text"
            class="bg-[#121212] border border-solid border-[#69AAE7] px-2 py-2 w-full"
          />
        </label>

        <label for="#remember" class="flex flex-row-reverse justify-end gap-2">
          Remember User
          <input type="checkbox" />
        </label>
        <div class="flex flex-col items-center gap-3">
          <button
            type="button"
            class="w-28 border border-solid border-[#69AAE7] uppercase py-2 px-3"
          >
            submit
          </button>
          <div class="text-sm flex gap-3">
            <router-link to="/">Forget Password</router-link>
            <router-link to="/login">Login User</router-link>
          </div>
        </div>
      </form>
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped></style>
