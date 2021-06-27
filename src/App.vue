<template>
  <div id="app">
    <Conversor/>
  </div>
</template>

<script>

import Conversor from "./components/Conversor.vue"

export default {
  name: "App",
  components: {
    Conversor
  }
}
</script>

<style>


#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background: initial;
  font-family: 'Roboto Mono', monospace;
  font-size: 1.2em;
  font-weight: bold;
  color: white;
}

</style>
