<template>
  <v-app id="app">
    <header>
      <Header></Header>
    </header>
    <v-main ma-7>
      <router-view/>
    </v-main>
    <footer centered>
      <Footer></Footer>
    </footer>
  </v-app>
</template>

<script>
import Header from './views/Header.vue'
import Footer from './views/Footer.vue'
export default {
  name: "App",
  components: {
    Header,
    Footer
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
