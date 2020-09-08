<template>
  <div class="bg-gray-800 h-screen">
    <div class="bg-gray-900 text-center md:text-left p-5">
      <router-link
        class="bg-gray-700 hover:bg-gray-600 text-gray-100 font-bold p-3 rounded-lg mr-3"
        to="/"
        >Home</router-link
      >
      <router-link
        class="bg-gray-700 hover:bg-gray-600 text-gray-100 font-bold p-3 rounded-lg"
        to="/about"
        >About</router-link
      >
    </div>
    <router-view />
  </div>
</template>
