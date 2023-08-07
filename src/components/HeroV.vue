<template>
  <v-parallax
  class="mt-16"
    dark
    src="https://static.wixstatic.com/media/84770f_2ba871a6b8ed4ed9811d8e14b50ad746~mv2.jpg/v1/fill/w_737,h_450,al_c,q_80,usm_0.66_1.00_0.01,enc_auto/84770f_2ba871a6b8ed4ed9811d8e14b50ad746~mv2.jpg"
  >
    <v-row
      align="center"
      justify="center"
    >
      <v-col
        class="text-left mb-16"
        cols="8"
      >
        <h2 class="text-h2 font-weight-medium mb-4 mr-16">
          Your Essentials
        </h2>
        <h2 class="text-h2 font-weight-medium mb-4 mr-16">
          for a Perfect
        </h2>
        <h2 class="text-h2 font-weight-medium mb-4 mr-16">
          Home Workout
        </h2>
        <v-hover
      v-slot="{ hover }"
    >
      <v-btn
        class="text-center text-capitalize d-flex.justify-end mt-6"
        :color="hover ? 'whait':'#a79579'"
        tile
        height="50px"
        width="180px"
      >
        Shop Now
      </v-btn>
    </v-hover>
      </v-col>
    </v-row>
  </v-parallax>
</template>
