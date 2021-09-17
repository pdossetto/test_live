<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <p>Ciao a tutti</p>
    
    <Jumbotron />
    <HelloWorld  />
    <HelloWorld />
    <HelloWorld />
    <HelloWorld />
    <HelloWorld />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Jumbotron from './components/Jumbotron.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Jumbotron
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
