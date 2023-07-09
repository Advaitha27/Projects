<template>
  <v-app class="grey lighten-4">
   
    <AppNavbar />
   <!-- <v-content>
   <router-view></router-view>
   </v-content> -->
  </v-app>
</template>

<script>
import AppNavbar from './components/AppNavbar'

export default {
  components: { AppNavbar },
  name: 'App',
  data () {
    return {
      
    }
  }
}
</script>