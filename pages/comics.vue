<template>
  <v-layout
    column
    justify-center
    align-center>
    <v-flex
      xs12
      sm8
      md6>
      <jean-eglinton-logo/>
      <v-card>
        <v-card-title>Comics</v-card-title>
        <rabbi/>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>
import JeanEglintonLogo from '~/components/JeanEglintonLogo.vue'
import Rabbi from '~/components/Rabbi.vue'

export default {
  components: {
    JeanEglintonLogo,
    Rabbi
  }
}
</script>
