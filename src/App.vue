<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <my-button size="small" @click="$emit('logout')" label="Search" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import MyButton from "./stories/Button.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    MyButton
  }
};
</script>

<style>
@import "./index.css";
</style>
