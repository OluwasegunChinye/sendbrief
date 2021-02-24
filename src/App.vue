<template>
  <v-app>
    <v-app-bar app prominent flat color="white">
      <div class="">
        <v-img alt="sendbrief logo" class="shrink ml-10 mt-13" contain src="./assets/logo.svg" transition="scale-transition" width="150" />
      </div> 
    </v-app-bar>
     
    <!-- <v-content> 
      <router-view></router-view>
    </v-content> -->

    <v-content class="mx-3">
      <Intro/>
    </v-content>
  </v-app>
</template>

<script>
import Intro from "@/components/Intro.vue"

export default {
  name: 'App',

  components: {
    Intro,

  },

  data: () => ({
    //
  }),
};
</script>
 <style lang="scss">
  @import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');

 #app {
  font-family: 'Montserrat', sans-serif;
}
 </style>