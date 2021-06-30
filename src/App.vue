<template>
  <div id="app">
    <Conversor />
  </div>
</template>

<script>
import Conversor from "./components/Conversor.vue";
export default {
  name: "App",
  components: {
    Conversor,
  },
};
</script>

<style>
html, body{
  margin: 0;
  padding: 0;
  height: 100%;
  width: 100%;
  background: linear-gradient(
    to right,
    rgb(127, 127, 213),
    rgb(134, 168, 231),
    rgb(145, 234, 228)
  );
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  height: 100%;
  width: 100%;
  text-align: center;
  color: #2c3e50;
  background: initial;
  font-family: "Roboto Mono", monospace;
  font-size: 1.2em;
  font-weight: bold;
  color: white;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}
</style>
