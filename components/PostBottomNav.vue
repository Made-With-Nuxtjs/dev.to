<template>
  <v-bottom-navigation
    :value="value"
    color="teal"
    grow
    fixed
  >
    <v-btn>
      <v-icon>mdi-heart-outline</v-icon>
    </v-btn>
    <v-btn>
      <v-icon>mdi-history</v-icon>
    </v-btn>

    <v-btn>
      <v-icon>mdi-map-marker</v-icon>
    </v-btn>
    <v-btn>
      <v-icon>mdi-map-marker</v-icon>
    </v-btn>
  </v-bottom-navigation>
</template>

<script>
export default {
  data: () => ({ value: 1 })
}
</script>
