<template>
  <div class="mood">
    <h1> The mood board for your interests. </h1>
    <Music />
  </div>
</template>

<script>
import Music from './Music.vue'

export default {
  name: 'MoodBoard',
  components: {
    Music
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
