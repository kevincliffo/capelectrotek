<template>
  <div id="app" class="bg-green-300 w-full h-full p-12">
    <div id="nav" class="flex items-center justify-between flex-wrap bg-teal-500 p-6">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>

</style>
