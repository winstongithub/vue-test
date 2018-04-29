<template>
  <div id="app">
    <img src="./assets/logo.png">
    <el-button @click="visible = false">Button</el-button>
    <InputUser/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld'
import InputUser from './components/InputUser'
export default {
  name: 'App',
  components: {
    InputUser
  }
}
</script>

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
