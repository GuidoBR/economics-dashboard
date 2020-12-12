<template>
  <div id="app">
    <Selic />
  </div>
</template>

<script>
import Selic from './components/Selic.vue'

export default {
  name: 'App',
  components: {
    Selic
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
