<template>
  <div id="app">
    <img alt="logo" src="./assets/favpng_movie-logo.png">
    <Message msg="Welcome to Your Movie Warehouse"/>
  </div>
</template>

<script>
import Message from './components/Message.vue'

export default {
  name: 'Movie Warehouse',
  components: {
    Message
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
