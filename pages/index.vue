<template>
  <v-layout
    column
    justify-center
    align-center
  >
    <v-flex
      xs12
      sm8
      md6
    >
      <div class="text-xs-center">
        <logo />
        <!-- <vuetify-logo /> -->
      </div>
      <v-card>
        <v-card-title class="headline">
          <p class="title"> Welcome to My Website </p>
        </v-card-title>
        <v-card-text>
        <p>
          About me, i would like to become an Expert of development JS.<br>
          This is my first site that uses nuxt.js. Let's go !<br>
        </p>

          <div class="text-xs-right">
            <em>we can do it<small> &mdash; Dia Demba</small></em>
          </div>
          <hr class="my-3">
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn
            color="primary"
            flat
            nuxt
            to="/inspire"
          >
            Continue
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>
import Logo from '~/components/Logo.vue'
// import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    // VuetifyLogo
  }
}
</script>


