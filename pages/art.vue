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
        <v-card-title>Art by Jean Eglinton</v-card-title>
        <v-card-text>
          <p>Coming Soon!</p>
          <cut-paper/>
          <torah-ark/>
        </v-card-text>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>
import JeanEglintonLogo from '~/components/JeanEglintonLogo.vue'
import CutPaper from '~/components/CutPaper.vue'
import TorahArk from '~/components/TorahArk.vue'

export default {
  components: {
    JeanEglintonLogo,
    CutPaper,
    TorahArk
  }
}
</script>
