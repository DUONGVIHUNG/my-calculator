<script>
import Calc from './components/Calculator.vue'
export default {
  name: 'app',
  components:{
    Calc
  }
}
</script>

<template>
  <div id="app">
    <Calc />
  </div>
</template>

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
