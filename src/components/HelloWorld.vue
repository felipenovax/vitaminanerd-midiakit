<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12">
        <v-img
          :src="require('../assets/logo.svg')"
          class="my-3"
          contain
          height="50"
        />
      </v-col>

      <v-col class="mb-4">
        <h1 class="display-2 font-weight-bold mb-3">
          Midia Kit V1
        </h1>

        <p class="subheading font-weight-regular">
          Enforço v1 midia kit vitamina nerd
          <a
            href="https://vitaminanerd.com.br"
            target="_blank"
          >Vitamina Nerd</a>
        </p>
      </v-col>

    </v-row>
  </v-container>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({
      //
    })
  }
</script>
