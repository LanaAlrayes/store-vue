<template>
  <div class="text mt-16"
  >
    <v-row
      align="center"
      justify="center"
      >
      <v-col
        class="text-center mb-16"
        cols="14"
        >
        <h3
          class="text-h3 text-center mt-14 mb-6 font-weight-bold text--primary"
          >
          The Best Equipment for <br/> Meeting Your Goals
        </h3>
        <h6
          class="text-h6 text-center font-weight-light text--disabled"
        >
          I'm a title. Click here to add your own text and edit me.
        </h6>
        <div class="d-flex align-center justify-center">
          <v-hover
           v-slot="{ hover }"
          >
          <v-btn
          class="text-center text-capitalize mt-4 mx-16"
          :color="hover ? '#424242':'black'"
          tile
          height="50px"
          width="180px"
          >
          <p class="mt-4 white--text">Shop All</p>
          </v-btn>
          </v-hover>
        </div>
      </v-col>
    </v-row>
  </div>
</template>
<style scoped>
.text{
  background:#a9977b;
}
</style>
