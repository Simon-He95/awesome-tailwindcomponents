<script setup lang="ts"></script>

<template>
  <div class="min-h-screen w-full flex items-center justify-center bg-gray-50">
    <div>
      <h1 class="mb-1 font-bold text-3xl flex gap-1 items-baseline font-mono">
        Form UI<span class="text-sm text-purple-700">form showcase</span>
      </h1>
      <div
        class="grid max-w-3xl gap-2 py-10 px-8 sm:grid-cols-2 bg-white rounded-md border-t-4 border-purple-400"
      >
        <div class="grid">
          <div
            class="bg-white flex min-h-[60px] flex-col-reverse justify-center rounded-md border border-gray-300 px-3 py-2 shadow-sm focus-within:shadow-inner"
          >
            <input
              id="first-name"
              type="text"
              name="first-name"
              class="peer block w-full border-0 p-0 text-base text-gray-900 placeholder-gray-400 focus:ring-0"
              placeholder="First name"
            >
            <label
              html="first-name"
              class="block transform text-xs font-bold uppercase text-gray-400 transition-opacity, duration-200 peer-placeholder-shown:h-0 peer-placeholder-shown:-translate-y-full peer-placeholder-shown:opacity-0"
            >First name</label>
          </div>
        </div>
        <div class="grid">
          <div
            class="bg-white first:flex min-h-[60px] flex-col-reverse justify-center rounded-md border border-gray-300 px-3 py-2 shadow-sm focus-within:shadow-inner"
          >
            <input
              id="last-name"
              type="text"
              name="last-name"
              class="peer block w-full border-0 p-0 text-base text-gray-900 placeholder-gray-400 focus:ring-0"
              placeholder="Last name"
            >
            <label
              html="last-name"
              class="block transform text-xs font-bold uppercase text-gray-400 transition-opacity, duration-200 peer-placeholder-shown:h-0 peer-placeholder-shown:-translate-y-full peer-placeholder-shown:opacity-0"
            >Last name</label>
          </div>
        </div>
        <div class="grid">
          <div
            class="bg-white flex min-h-[60px] flex-col-reverse justify-center rounded-md border border-gray-300 px-3 py-2 shadow-sm focus-within:shadow-inner"
          >
            <input
              id="last-name"
              type="text"
              name="last-name"
              class="peer block w-full border-0 p-0 text-base text-gray-900 placeholder-gray-400 focus:ring-0"
              placeholder="Company"
            >
            <label
              html="company"
              class="block transform text-xs font-bold uppercase text-gray-400 transition-opacity, duration-200 peer-placeholder-shown:h-0 peer-placeholder-shown:-translate-y-full peer-placeholder-shown:opacity-0"
            >Company</label>
          </div>
        </div>
        <div class="grid">
          <div
            class="bg-white flex min-h-[60px] flex-col-reverse justify-center rounded-md border border-gray-300 px-3 py-2 shadow-sm focus-within:shadow-inner"
          >
            <input
              id="email"
              type="email"
              name="email"
              class="peer block w-full border-0 p-0 text-base text-gray-900 placeholder-gray-400 focus:ring-0"
              placeholder="E-mail"
            >
            <label
              html="email"
              class="block transform text-xs font-bold uppercase text-gray-400 transition-opacity, duration-200 peer-placeholder-shown:h-0 peer-placeholder-shown:-translate-y-full peer-placeholder-shown:opacity-0"
            >E-mail</label>
          </div>
        </div>
        <button
          type="submit"
          class="mt-4 bg-purple-500 text-white py-2 px-6 rounded-md hover:bg-purple-600"
        >
          Login
        </button>
      </div>
    </div>
  </div>
</template>

<style scope></style>
