<template>
  <v-app>
    <v-layout justify-center align-center>
      <v-flex xs12 sm8 md6 lg5 xl4>
        <v-card class="elevation-6">
          <v-toolbar color="primary" dark card>
            <v-toolbar-title>
              Ingresa tus Credenciales
            </v-toolbar-title>
          </v-toolbar>
          <v-card-text>
            <v-text-field label="Email"></v-text-field>
            <v-text-field label="Password"></v-text-field>
          </v-card-text>
          <v-card-text>
            <v-layout justify-end>
              <v-btn color="primary" @click="enviarInformacion">Ingresar</v-btn>
            </v-layout>
          </v-card-text>
        </v-card>
      </v-flex>
    </v-layout>
  </v-app>
</template>

<script>

export default {
  name: 'App',
  data () {
    return {
      //
    }
  }
}
</script>
