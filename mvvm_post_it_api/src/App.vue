<template>
  <div id="app">
    <h1>Hello Thibaow</h1>
    <post_it_board msg="lo and behold! "/>
  </div>
</template>

<script>
import post_it_board from './components/post_it_board.vue'

export default {
  name: 'App',
  components: {
    post_it_board
  }
}
</script>

<style lang="scss">
</style>
