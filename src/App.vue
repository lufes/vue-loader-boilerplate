<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style lang="sass">
@import '../node_modules/bootstrap/dist/css/bootstrap.min.css'
@import '../node_modules/@fortawesome/fontawesome-free/css/fontawesome.css'
@import '../node_modules/@fortawesome/fontawesome-free/css/brands.css'
@import '../node_modules/@fortawesome/fontawesome-free/css/regular.css'
@import '../node_modules/@fortawesome/fontawesome-free/css/solid.css'

#app
  font-family: 'Avenir', Helvetica, Arial, sans-serif
  -webkit-font-smoothing: antialiased
  -moz-osx-font-smoothing: grayscale
  text-align: center
  color: #2c3e50
  margin-top: 60px
</style>
