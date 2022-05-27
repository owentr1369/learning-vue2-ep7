<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <h1>Hello</h1>
    <div>{{ test }}</div>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      test: "Hello Vietnam",
    };
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
