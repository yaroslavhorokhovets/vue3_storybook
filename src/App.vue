<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <InboxScreen />
    <my-button size="small" @click="$emit('logout')" label="Search" />
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import MyButton from "./stories/Button.vue";
import InboxScreen from './components/InboxScreen.vue';
export default {
  name: "App",
  components: {
    // HelloWorld,
    MyButton,
    InboxScreen,
  }
};
</script>

<style>
@import "./index.css";
</style>
