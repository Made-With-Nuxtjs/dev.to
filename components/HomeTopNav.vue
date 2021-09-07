<template>
  <v-card flat>
    <v-tabs
      color="deep-purple accent-4"
      right
    >
      <v-toolbar-title><h3>Posts</h3></v-toolbar-title>
      <v-spacer />
      <v-tab>
        <nuxt-link to="/">
          Feed
        </nuxt-link>
      </v-tab>
      <v-tab>
        <nuxt-link to="/week">
          Week
        </nuxt-link>
      </v-tab>
      <v-tab>
        <nuxt-link to="/month">
          Month
        </nuxt-link>
      </v-tab>
      <v-tab>
        <nuxt-link to="/year">
          Year
        </nuxt-link>
      </v-tab>
      <v-tab>
        <nuxt-link to="/infinity">
          Infinity
        </nuxt-link>
      </v-tab>
      <v-tab>
        <nuxt-link to="/latest">
          Latest
        </nuxt-link>
      </v-tab>
    </v-tabs>
  </v-card>
</template>
