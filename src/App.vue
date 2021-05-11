<template>
  <div id="app">
    <Box />

    <Img />

    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import Box from "./components/Box.vue";
import HelloWorld from "./components/HelloWorld.vue";
import Img from "./components/Img.vue";

export default {
  name: "App",
  components: {
    HelloWorld,

    Box,

    Img,
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
