<template>
  <div>
    <my-header/>
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.2.0/css/all.css" integrity="sha384-hWVjflwFxL6sNzntih27bfxkr27PmbbK/iSvJ+a4+0owXq79v+lsFkW54bOGbiDQ" crossorigin="anonymous">
    <div id="app">
      <!--    <img src="./assets/logo.png">-->
    <router-view/>
  </div>
    <my-footer/>
  </div>
</template>

<script>import Header from './components/partials/Header'
import Footer from './components/partials/Footer'
export default {
  components: {'my-header': Header, 'my-footer': Footer},
  name: 'App'
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
