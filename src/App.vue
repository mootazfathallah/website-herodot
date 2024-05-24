<template>
  <academy msg="Welcome to Your Vue.js App"/>
</template>

<script>
import academy from './components/academy.vue'

export default {
  name: 'App',
  components: {
    academy
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
  margin-top: 30px;
}
body{
  background-color: rgb(0, 0, 0);
}
</style>
