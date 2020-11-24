<template>
  <div id="app">
    <header>
      <h1 id="title">Hello Thibaow</h1>
    </header>
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
#app {
  padding:0px;
  margin:0px;
  width:100%;
  font-family: Andale Mono, monospace;
}

header {
  height: 50px;
  width:100%;
  margin-bottom:10px;
  vertical-align: middle;
  box-shadow:0px 10px 10px grey;
  background: linear-gradient(217deg, rgba(255,0,0,.8), rgba(255,0,0,0) 70.71%),
            linear-gradient(127deg, rgba(0,255,0,.8), rgba(0,255,0,0) 70.71%),
            linear-gradient(336deg, rgba(0,0,255,.8), rgba(0,0,255,0) 70.71%);
}

#title{
    vertical-align:center;
    padding-top:5px;
    padding-bottom:5px;
    padding-left:10px;

}
</style>
