<template>
  <v-app id="inspire">
    <v-parallax height="900" class="ma-0" src="./assets/parallaxbg.png">
    <v-navigation-drawer
      v-model="drawer"
      app
    >
      <!--  -->
    </v-navigation-drawer>

    <v-app-bar 
      color="rgba(255,255,255, 0.15)" 
      :elevation="0" 
      app>
      <v-app-bar-nav-icon color="#000000" @click="drawer = !drawer"></v-app-bar-nav-icon>

      <v-toolbar-title><v-img src="" max-height="25"></v-img></v-toolbar-title>
    </v-app-bar>

    <v-main>
    </v-main>
    </v-parallax>
  </v-app>
</template>

<script>
  export default {
    data: () => ({ drawer: false }),
  }
</script>
