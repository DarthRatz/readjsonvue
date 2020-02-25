<template>
  <div id="app">
    <Json/>
  </div>
</template>

<script>
import Json from "./components/Json";

export default {
  name: "App",
  components: {
    Json
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
