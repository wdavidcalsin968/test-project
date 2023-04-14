<script setup lang="ts">
import { Icon } from "@iconify/vue";
</script>

<template>
  <div class="grid place-items-center w-screen min-h-screen bg-black">
    <div
      class="border border-solid border-[#69AAE7] text-[#69AAE7] flex flex-col gap-3 p-11 w-96"
    >
      <h2 class="uppercase text-center font-semibold text-2xl">login</h2>
      <form action="" class="flex flex-col gap-5">
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
        <div class="flex flex-col items-center gap-5">
          <router-link
            to="/dashboard"
            class="w-28 border border-solid border-[#69AAE7] uppercase py-2 px-3 text-center"
            >submit</router-link
          >
          <div class="text-sm flex gap-3">
            <router-link to="/">Forget Password</router-link>
            <router-link to="/register">Register User</router-link>
          </div>
          <div class="flex gap-4">
            <Icon
              icon="logos:google-icon"
              width="30"
              :inline="true"
              class="cursor-pointer transition delay-100 hover:scale-110"
            />
            <Icon
              icon="logos:facebook"
              width="30"
              :inline="true"
              class="cursor-pointer transition delay-100 hover:scale-110"
            />
          </div>
        </div>
      </form>
    </div>
  </div>
</template>

<style scoped></style>
