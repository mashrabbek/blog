<template>
  <div style="background-color: blue">
    <!-- content title  -->
    <v-row class="pa-5" style="background-color: darkslateblue">
      <v-col cols="12" justify="center" align="center">
        <v-img
          :src="require('~/assets/me.JPG')"
          height="200"
          width="200"
          style="border-radius: 50%"
        >
        </v-img>
      </v-col>
      <v-col cols="12" justify="center" align="center">
        <p>Software Developer</p>
        <h2>AKBAROV MASHRABBEK</h2>
      </v-col>
    </v-row>
    <!-- -->
    <v-row class="pa-5" style="background-color: grey">
      <v-col cols="12" justify="center" align="center"> </v-col>
    </v-row>
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";
import VuetifyLogo from "~/components/VuetifyLogo.vue";

export default {
  components: {
    Logo,
    VuetifyLogo
  }
};
</script>
