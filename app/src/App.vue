<template>
  <div id="app">
       这里是git测试
       <Login></Login>
  </div>
</template>

<script>
 import Login from "./components/login"

export default {
  name: 'app',
  components: {
   Login
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center; 
  color: #2c3e50;
  margin-top: 60px;
}
</style>
