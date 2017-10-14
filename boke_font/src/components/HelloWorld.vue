<template>
  <div class="hello">
    <div class="head">
      <div class="left"><img src="../img/head.jpg" alt=""><h1>麒.萱萱</h1></div>
    </div>
    <navs></navs>
    <div class="cont">
      <boke></boke>
      <asides></asides>
    </div>
  </div>
  
</template>

<script>
import navs from "./Nav"
import boke from "./Boke"
import asides from "./Aside"
export default {
  name: 'HelloWorld',
  data () {
    return {
      
      }
  },
  components:{
    navs,
    boke,
    asides
  }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;

}
ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
  text-decoration: none;
}
.hello{
  width:100%;
  height:100%;
}
.head{
  width:100%;
}
.left{
  width:430px;
}
.left img{
  border-radius: 50%;
  margin:20px 0px 0px 40px;
}
.left h1{
  padding-top:90px;
  font-weight: 700;
  font-size:50px;
  float: right;
}
.cont{
  width:1500px;
  height:500px;
  margin:auto;
  margin-top: 60px;
}

</style>
