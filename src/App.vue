<template>
  <v-app>
    <h1>oi</h1>
  <v-navigation-drawer app  style="background-color: green;">
    <h1>oi</h1>
  </v-navigation-drawer>

  <v-app-bar app  style="background-color: red;">
    <h1>oi</h1>
  </v-app-bar>

  <!-- Sizes your content based upon application components -->
  <v-main  style="background-color: yellow;">

    <!-- Provides the application the proper gutter -->
    <v-container fluid>
      <h1>oi</h1>
      <!-- If using vue-router -->
      <router-view></router-view>
    </v-container>
  </v-main>

  <v-footer app  style="background-color: blue;">
    <h1>oi</h1>
  </v-footer>
</v-app>
</template>

<script>


export default {
  name: 'App',

  components: {

  },

  data: () => ({
    //
  }),
};
</script>

<style lang="sass" scoped>
.container
  display: grid
  grid-template-columns: 1fr 1fr
</style>
