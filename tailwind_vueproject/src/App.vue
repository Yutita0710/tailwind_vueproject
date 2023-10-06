<template>
  <HelloWorld />
  <div class="bg-gray-200 p-4">
    <h1 class="text-2xl font-bold">
      Welcome to my Vue 3 project with Tailwind CSS!
    </h1>
    <p class="text-lg mt-4">
      Let's explore the power of Tailwind CSS in Vue 3.
    </p>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
