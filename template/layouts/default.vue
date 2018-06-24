<template>
  <v-app light>
    <v-toolbar fixed class="white">
      <v-toolbar-title>Your Logo</v-toolbar-title>
    </v-toolbar>
    <nuxt/>
    <v-footer class="blue darken-2">
      <v-layout row wrap align-center>
        <v-flex xs12>
          <div class="white--text text-xs-center">
            Powered
            <v-icon class="red--text">favorite</v-icon>
            by <a class="white--text" href="//kola.design">Kola Design</a>
          </div>
        </v-flex>
      </v-layout>
    </v-footer>
  </v-app>
</template>