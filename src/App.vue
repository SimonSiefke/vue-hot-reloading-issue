<template>
  <div id="app">
    {{ count }}
  </div>
</template>

<script>
export default {
  data() {
    return {
      count: 2
    };
  }
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  font-size: 60px;
}
</style>
