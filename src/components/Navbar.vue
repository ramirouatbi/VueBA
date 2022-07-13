<template>
    <v-app-bar app color="#00008B" dark class="px-8 my-nav">
      <v-app-bar-nav-icon @click="drawer = true" class="d-flex d-sm-none" ></v-app-bar-nav-icon>
      <v-tabs
            v-model="tab"
            align-with-title
            class="d-none d-sm-flex" 
          >
        <v-btn icon>
            <v-icon color="E1F39E">{{icon}}</v-icon>
        </v-btn>
        <v-spacer> </v-spacer>
            <v-btn text>Startseite</v-btn>
            <router-link to="/Produkte"><v-btn text>Produkte</v-btn></router-link>
            <v-btn text>Dienste</v-btn>
            <v-btn text>Über uns</v-btn>
            <v-btn text>News</v-btn>
            <v-btn text>Kontakt</v-btn>
            </v-tabs>
    </v-app-bar>
</template>

<script>
  import HelloWorld from '../components/HelloWorld'

  export default {
    name: 'Home',

    components: {
      HelloWorld,
    },
    data(){
        return{
        icon : 'fas fa-tree ',
        drawer: false,
      tab: null,
    }
    }
    
  }
</script>

<style scoped>




</style>