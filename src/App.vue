<template>
  <v-app>
    
  <v-toolbar dark color="primary" app>
    <v-toolbar-side-icon></v-toolbar-side-icon>
    <v-toolbar-title class="white--text">Title</v-toolbar-title>
    <v-spacer></v-spacer>
    <v-btn icon>
      <v-icon>more_vert</v-icon>
    </v-btn>
  </v-toolbar>  

    <v-content>
      <HelloWorld/>
    </v-content>
    <v-footer class="pa-3" color="primary lighten-1">
     <v-spacer></v-spacer> 
     <div>&copy;2018 askander</div>
    </v-footer>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data () {
    return {
      //
    }
  }
}
</script>
