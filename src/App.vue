<template>
  <v-app>
    <v-main>
      <!-- <v-container> -->
      <v-row>
        <v-col cols="6">
          <HelloWorld />
        </v-col>
        <v-col cols="6">
          <v-img
            src="/images/workstation-awm.jpg"
            alt="AWM Workstation"
          ></v-img>
        </v-col>
      </v-row>
      <!-- </v-container> -->
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue"

export default {
  name: "App",

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
}
</script>
