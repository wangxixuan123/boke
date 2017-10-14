<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
*{
  margin:0;
  padding:0px;
}
html,body{
  width:100%;
  height:100%;
}
body{
  /*font-family: Alegreya, serif;*/
  font-family: YouYuan,serif;
  background:url('img/timg1.gif') no-repeat;
  background-size:100% 100%;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
