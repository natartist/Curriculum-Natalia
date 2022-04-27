<template>
  <div id="app">
    <NavBar/>
    <MiCv/>
    <Footer/>
    <!-- <Portafolio/> -->
  </div>
</template>

<script>

import NavBar from "./components/Navbar.vue";
import MiCv from "./components/MiCv.vue";
import Footer from "./components/Footer.vue"
// import Portafolio from "./components/Portafolio.vue"

export default {
  name: 'App',
  components: {
    MiCv,
    NavBar,
    Footer, 
    // Portafolio
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
