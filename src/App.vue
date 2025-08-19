<template>
  <img alt="Vue logo" src="./assets/venado.jpg" width="15%0"/>
  <HelloWorld msg="P R O C E S O"/>
  <FooterYoo/>

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import FooterYoo from './components/FooterYoo.vue'


export default {
  name: 'App',
  components: {
    HelloWorld,
    FooterYoo
  
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
