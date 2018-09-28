<template>
  <v-layout
    column
    justify-center
    align-center>
    <v-flex
      xs12
      sm8
      md6>
      <div class="text-xs-center">
        <jean-eglinton-logo/>
      </div>
      <v-card>
        <img 
          src="../assets/hineini.jpg" 
          alt="Hineini"
        >
        <v-card-actions>
          <v-spacer/>
          <v-btn
            color="info"
            flat
            nuxt
            to="/comics">Read Appalachian Rabbi Avatar</v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>
import JeanEglintonLogo from '~/components/JeanEglintonLogo.vue'

export default {
  components: {
    JeanEglintonLogo
  }
}
</script>

<style>
img {
  width: 100% !important;
  text-align: center;
}
</style>
