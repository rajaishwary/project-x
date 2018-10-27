<template>
  <div id="app">
    <Header title="Header Title"/>
    <MainContainer />
    <Footer title="Footer"/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import MainContainer from './components/MainContainer.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'app',
  components: {
    Header,
    MainContainer,
    Footer
  }
}
</script>

<style>
body {
  margin: 0;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0;
}
</style>
