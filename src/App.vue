<template>
  <v-app>
    <v-app-bar
      app
      color="grey"
      dark
    >
      <div class="d-flex align-center">
        <v-img
          :src="require('./assets/logo.png')"
          alt="Vuetify Name"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="100"
          width="100"
        />
      </div>

      <v-spacer></v-spacer>

      <v-btn
        href="https://vitaminanerd.com.br"
        target="_blank"
        text
      >
        <span class="mr-2">Acessar</span>
        <v-icon>mdi-open-in-new</v-icon>
      </v-btn>
    </v-app-bar>

    <v-content>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
