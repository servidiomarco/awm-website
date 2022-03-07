<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12">
        <v-img :src="logo" class="my-3" contain height="200" />
      </v-col>

      <v-col class="mb-4">
        <h1 class="display-2 font-weight-bold mb-3">
          Our website is under construction.
        </h1>

        <h4>We'll be here soon with our new awesome site.</h4>

        <!-- <p class="subheading font-weight-regular">Get in touch</p> -->
      </v-col>

      <v-col class="mb-5" cols="12">
        <h2 class="headline font-weight-bold mb-5">Get in touch</h2>

        <v-row justify="center"> </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import logo from "../assets/logo-awm-web.png"

export default {
  name: "Awm coming soon page",

  data: () => ({
    logo,
  }),
}
</script>
