<template>
  <!-- <img class="dolan-img" alt="DolanLabs logo" src="./assets/dolanwithtext-logo.png"> -->
  <HelloWorld msg="Lorem Ipsum dolor sir amet"/>
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
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display&family=Poppins&display=swap');

* {
  background: #4060FF;
}
#app {
  /* font-family: "Playfair Display", Helvetica, Arial, sans-serif; */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #F2F2F2;
  margin-top: 60px;
}
</style>
