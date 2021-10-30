<template>
  <issues :key="n" v-for="n in 10"></issues>
</template>

<script>

import Issues from "./components/Issues";

export default {
  name: "App",
  components: {
    Issues
  },
};
</script>

<style>
html,
body {
  height: 100%;
}

p {
  margin: 0;
}

body {
  margin: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
</style>
