<template>
  <v-row no-gutters>
    <v-col
      cols="8"
      offset-md="2"
    >
      <v-container class="py-0 fill-height">
        <nuxt-link to="#" class="text-decoration-none">
          <v-avatar
            color="black"
            size="48"
          >
            <v-icon size="50" class="white--text">
              mdi-dev-to
            </v-icon>
          </v-avatar>
        </nuxt-link>
        <v-responsive max-width="400" class="ml-3">
          <v-text-field
            dense
            flat
            hide-details
            solo
            placeholder="Search"
            outlined
            append-icon="mdi-magnify"
          />
        </v-responsive>
        <v-spacer />
        <v-responsive max-width="400">
          <v-btn
            depressed
          >
            <nuxt-link to="#" class="text-decoration-none">
              Log in
            </nuxt-link>
          </v-btn>
          <nuxt-link to="#" class="text-decoration-none">
            <v-btn
              depressed
              color="primary"
            >
              Create Account
            </v-btn>
          </nuxt-link>
        </v-responsive>
      </v-container>
    </v-col>
  </v-row>
</template>
