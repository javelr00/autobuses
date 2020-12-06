<template>
  <v-app>
    <v-app-bar
      app
      color="red darken-2"
      dark
    >
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7c/Escudo_de_Le%C3%B3n.svg/1200px-Escudo_de_Le%C3%B3n.svg.png"
          transition="scale-transition"
          width="40"
        />
      </div>

      <span class="mr-2">Autobuses de León</span>

      <v-spacer></v-spacer>
      <v-spacer></v-spacer>
      <v-spacer></v-spacer>
      <v-spacer></v-spacer>
      <v-spacer></v-spacer>
      <v-spacer></v-spacer>
      <v-spacer></v-spacer>
      <v-btn text>Inicio</v-btn>
      <v-spacer></v-spacer>
      <v-btn text>Tarifas</v-btn>
      <v-spacer></v-spacer>
      <v-btn text>Mapa</v-btn>
      <v-spacer></v-spacer>
      <v-btn text>Líneas disponibles</v-btn>
      <v-spacer></v-spacer>
      <v-btn text>MetroMinuto</v-btn>

    </v-app-bar>

    <v-main>
      <HelloWorld/>
    </v-main>
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
