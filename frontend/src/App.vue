<template>
  <div id="app">
    <img src="./assets/logo-klas.png">
    <router-view/>
    <shortener-form/>
  </div>
</template>

<script>
import ShortenerForm from './components/ShortenerForm'
export default {
  name: 'App',
  components: {
    ShortenerForm
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
