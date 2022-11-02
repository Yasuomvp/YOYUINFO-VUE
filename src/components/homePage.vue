<template>

  <v-bottom-navigation
    :value="value"
    color="#F06292"
  >
    <v-btn>
      <span>Home</span>

      <v-icon>mdi-home</v-icon>
    </v-btn>

    <v-btn>
      <span>Favorites</span>

      <v-icon>mdi-heart</v-icon>
    </v-btn>

    <v-btn>
      <span>Nearby</span>

      <v-icon>mdi-map-marker</v-icon>
    </v-btn>
  </v-bottom-navigation>


</template>

<script>
export default {
  name: "homePage"
}
</script>

<style scoped>

</style>
