<template>
  <div id="app">
    <CompBinding/>
  </div>
</template>

<script>
import CompBinding from './components/CompBinding.vue'

export default {
  name: 'App',
  components: {
    CompBinding,
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
  margin-top: 60px;
}
</style>
