<template>
  <v-card flat>
    <v-tabs
      color="deep-purple accent-4"
    >
      <v-card-title class="float-start">
        Post
      </v-card-title>
      <v-spacer />
      <v-tabs-slider color="blue" />
      <v-tab>
        <nuxt-link to="/" class="text-decoration-none">
          Feed
        </nuxt-link>
      </v-tab>
      <v-tab>
        <nuxt-link to="/week" class="text-decoration-none">
          Week
        </nuxt-link>
      </v-tab>
      <v-tab>
        <nuxt-link to="/month" class="text-decoration-none">
          Month
        </nuxt-link>
      </v-tab>
      <v-tab>
        <nuxt-link to="/year" class="text-decoration-none">
          Year
        </nuxt-link>
      </v-tab>
      <v-tab>
        <nuxt-link to="/infinity" class="text-decoration-none">
          Infinity
        </nuxt-link>
      </v-tab>
      <v-tab>
        <nuxt-link to="/latest" class="text-decoration-none">
          Latest
        </nuxt-link>
      </v-tab>
    </v-tabs>
  </v-card>
</template>
