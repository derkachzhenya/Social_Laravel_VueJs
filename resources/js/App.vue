<template>
  <h1 class="text-4xl font-bold underline text-center mb-5 mt-5">
    Hello world!
  </h1>
  <div><router-link to="index">Index</router-link></div>
  <div><router-link to="page">Page</router-link></div>
  
  <router-view></router-view>
</template>

<script>
export default {
  name: "App",
};
</script>


<style>
</style>