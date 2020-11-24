<template>
  <div id="app">
    <h1>Hello Thibaow</h1>
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <post_it_board msg="lo and behold! "/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import post_it_board from './components/post_it_board.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    post_it_board
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
