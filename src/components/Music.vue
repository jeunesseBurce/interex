<template>
  <div class="music">
    <h1> Music </h1>
    <div class="container">
        <img alt="Music 1" src="../assets/music1.jpeg" width="300" height="450">
        <img alt="Music 2" src="../assets/music2.jpeg" width="300" height="450">
    </div>
  </div>
</template>

<script>
export default {
  name: 'Music'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container {
    display: inline-grid;
    grid-gap: 15px 10px;
}
</style>
