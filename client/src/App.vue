<template>
  <div id="app">
    <h1>{{ message }}</h1>
    <router-link to="/text-input">Go to Text Input</router-link>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 'Hello from Vue!',
    };
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1 {
  font-size: 2em;
  margin-bottom: 20px;
}
</style>