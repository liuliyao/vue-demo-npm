<template>
  <div id="app">
    <img alt="logo" src="./assets/logo.png">
    <title-txt title="vue制作发布npm包" />
  </div>
</template>

<script>
import TitleTxt from './components/TitleTxt'

export default {
  name: 'App',
  components: {
    TitleTxt
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
