<template>
  <div id="app">
    <AboutUs/>
  </div>
</template>



<script>
import AboutUs from './components/About_us.vue'

export default {
  name: 'App',
  components: {
    AboutUs
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  scroll-behavior: smooth;
  background-color: rgba(137, 137, 137, 0.557);
}
</style>
