<template>
  <v-app>
    <div id="container">
      <app-navigation/>
      <app-dashboard/>
    </div>
    <app-footer/>
  </v-app>
</template>

<style scoped>
  #container {
    display: flex;
    height: 100%;
  }
</style>

<script>
import Dashboard from './components/Dashboard'
import Navigation from './components/Navigation'
import Footer from './components/Footer'

export default {
  name: 'App',

  components: {
    'app-dashboard': Dashboard,
    'app-navigation': Navigation,
    'app-footer': Footer
  },

  data: () => ({
    //
  }),
};
</script>
