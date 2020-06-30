<template>
  <div id="app">
    <div class="min-h-screen bg-gray-100">
      <div class="min-h-screen flex">
        <div class="w-2/12 bg-gray-700">
          <img
            src="./assets/logo.png"
            alt="Vueser"
            class="flex items-center img-brand"
          />
          <router-link to="/" class="block text-gray-200 mt-5 p-5"
            >Home</router-link
          >
          <router-link to="/about">About</router-link>
        </div>
        <div class="flex-1">
          <router-view />
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.img-brand {
  width: 50px;
  text-align: center;
}
</style>
