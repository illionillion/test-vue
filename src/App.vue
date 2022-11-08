<template>
  <img alt="Vue logo" src="./assets/logo.png" onclick="alert('OK')">
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <HelloVue msg="Hello Vue"/>
  <CountApp/>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import HelloVue from './components/HelloVue.vue';
import CountApp from './components/Count.vue';

export default {
  name: 'App',
  components: {
    // HelloWorld,
    HelloVue,
    CountApp
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
