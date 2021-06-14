<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>Browse Movies</h3>
      <br>
      <a href="./view/movies.vue" target="_blank" rel="noopener">Movies</a>
    <h3>Browse Series</h3>
      <br>
      <a href="series.vue" target="_blank" rel="noopener">Series</a>
  </div>
<script>
export default {
  name: 'App',
  props: {
    msg: String
  }
}
</script>


