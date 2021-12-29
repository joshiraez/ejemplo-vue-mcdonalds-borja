<template>
  <div id="app">
    <Contenedor />
  </div>
</template>

<script>
import Contenedor from "./components/Contenedor";

export default {
  name: "App",
  components: {
    Contenedor,
  },
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
