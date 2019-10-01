<template>
  <v-layout column justify-center align-center>
    <v-flex xs12 sm8 md6>
      <div class="text-xs-center">
        <focan-logo />
      </div>
      <v-card>
        <v-card-title class="headline">
          <h2>SITIO EN CONSTRUCCIÓN</h2>
        </v-card-title>
        <!-- <v-card-text>
          <p>Fondo para el Cuidado Animal</p>
          <p>Sitio en construcción</p>
        </v-card-text> -->
        <!-- <v-card-actions>
          <v-spacer />
          <v-btn color="primary" flat nuxt to="/inspire">Continue</v-btn>
        </v-card-actions> -->
      </v-card>
    </v-flex>
  </v-layout>
</template>

<style scoped>
.headline {
  display: flex;
  justify-content: center;
}
</style>

<script>
import FocanLogo from '~/components/FocanLogo.vue'

export default {
  components: {
    FocanLogo
  }
}
</script>
