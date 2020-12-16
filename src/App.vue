<template>
  <div id="app">
    <Header />
  </div>
</template>

<script>
import Header from './components/layout/Header.vue'


export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style>
* {
    box-sizing: inherit;
    margin: 0;
    padding: 0;
  }

  html {
    font-size: 62.5%;
    box-sizing: border-box;
    scroll-behavior: smooth;
  }

  body {
    font-family: Arial, Helvetica, sans-serif;
    line-height: 1.4;
  }

</style>
