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
        <v-card-title>About Jean</v-card-title>
        <v-card-text>
          <bio/>
          <contact/>
        </v-card-text>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>
import JeanEglintonLogo from '~/components/JeanEglintonLogo.vue'
import Bio from '~/components/Bio.vue'
import Contact from '~/components/Contact.vue'

export default {
  components: {
    JeanEglintonLogo,
    Bio,
    Contact
  }
}
</script>

<style>
img {
  width: 100% !important;
  text-align: center;
}
</style>
