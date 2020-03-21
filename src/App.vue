<template>
  <div id="app">
    <img alt="Interex logo" src="./assets/interex-logo.jpg" width="300" height="300">
    <MoodBoard />
  </div>
</template>

<script>
import MoodBoard from './components/MoodBoard.vue'

export default {
  name: 'App',
  components: {
    MoodBoard
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
