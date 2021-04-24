<template>
  <div id="app">
    <img alt="Vue logo" src="https://vuejs.org/images/logo.png" width="100">
    <HelloWorld msg="Добро пожаловать в ваше приложение Vue.js "/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
  margin-top: 20px;
}
</style>
