<template>
  <v-app>
      <app-bar/>
    <v-main>
     <router-view />
    </v-main>
    <footer-v />
  </v-app>
</template>

<script>
import AppBar from './components/AppBar'
import FooterV from './components/footerV.vue'

export default {
  name: 'App',

  components: {
    AppBar,
    FooterV
  },

  data: () => ({
    //
  })
}
</script>
