<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your 뷰JS App"/>
    <GreetingUser/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import GreetingUser from './components/GreetingUser.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    GreetingUser
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
  margin-top: 60px;
}
</style>
