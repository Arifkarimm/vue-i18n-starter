<template>
  <div id="app">
    <HelloI18n />

    <Navbar />
    <router-view />
  </div>
</template>

<script>
import HelloI18n from "./components/HelloI18n.vue";
import Navbar from "./components/Navbar.vue";

export default {
  name: "App",
  components: {
    HelloI18n,
    Navbar,
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
