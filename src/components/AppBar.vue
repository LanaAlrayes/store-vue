<template>
  <div>
    <v-app-bar
    cols="6"
    md="4"
    absolute
    color="white"
    dense
    prominent
    height="30px"
    scroll-target="#scrolling-techniques-7"
    >
      <template
      #extension>
      <div class="black">
        <v-toolbar-title class="white--text font-weight-black mt-2 mx-16">GEAR UP.</v-toolbar-title>
      </div>
         <v-tabs
        color="black"
        class="ml-16 text-h5"
      >
        <v-tab>
          Home
        </v-tab>
        <v-tab>
         Shop All
        </v-tab>
        <v-tab>
          Contact
        </v-tab>
      </v-tabs>
      <div
        cols="6"
        md="4"
        class="d-flex flex-row mr-16"
      >
        <v-btn
          class="mx-1 mb-2"
          fab
          x-small
          color="white"
        >
          <v-icon
          >
            {{ icons.account }}
          </v-icon>
        </v-btn>
        <v-btn
          class="mx-1 mb-2"
          fab
          x-small
          color="white"
        >
          <v-icon
          >
            {{ icons.facebook }}
          </v-icon>
        </v-btn>
        <v-btn
          class="mx-1 mb-2"
          fab
          x-small
          color="white"
        >
          <v-icon
          >
            {{ icons.youtube }}
          </v-icon>
        </v-btn>
        <v-btn
          class="mx-1 mb-2"
          fab
          x-small
          color="white"
        >
          <v-icon
          >
            {{ icons.instagram }}
          </v-icon>
        </v-btn>
        </div>
      </template>
    </v-app-bar>
  </div>
</template>
<script>
export default {
  name: 'App',
  data: () => ({
    icons: {
      account: ' mdi-account',
      facebook: 'mdi-facebook',
      youtube: 'mdi-youtube',
      instagram: 'mdi-instagram'
    }
  })
}
</script>
