<template>
  <div id="app">
    
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <hero/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import hero from './components/hero.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    hero
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
