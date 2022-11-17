<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <ClockScreen msg="Welcome to Your Vue.js App" />
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import ClockScreen from "./components/ClockScreen.vue";

export default {
  name: "App",
  components: {
    // HelloWorld
    ClockScreen,
  },
};
</script>

<style>
html,
body {
  height: 100%;
  margin: unset;
}

#app {
height: 100%;
}
</style>
