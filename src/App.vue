<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <img src="./assets/test.jpg" class="resizable-image" />
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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

.resizable-image {
  width: 200px; /* Adjust the width as per your requirement */
  height: auto; /* Automatically adjust the height to maintain the aspect ratio */
}
</style>
