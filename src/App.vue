<template>
  <Auth v-if="0"></Auth>
  <HomePage v-if="1"></HomePage>
</template>

<script>
import Auth from './components/authPage'
import HomePage from './components/homePage'


export default {
  name: 'App',
  components: {
    Auth,
    HomePage
  }
}
</script>

<style>
body{
  background-color: #F8F9FA;
}
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
