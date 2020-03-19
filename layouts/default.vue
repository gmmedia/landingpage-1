<template>
  <v-app>
    <headerComp />
    <nuxt />
    <footerComp />
  </v-app>
</template>

<script>
import headerComp from "~/components/headerComp"
import footerComp from "~/components/footerComp"

export default {
  components: {
    headerComp,    
    footerComp
  },  
};
</script>

<style>
</style>
