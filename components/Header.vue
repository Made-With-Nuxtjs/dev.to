<template>
  <v-row no-gutters>
    <v-col
      cols="12"
      offset-md="2"
    >
      <v-container class="fill-height">
        <nuxt-link to="/" class="text-decoration-none">
          <v-icon
            color="black"
            size="70"
          >
            mdi-dev-to
          </v-icon>
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
        <v-responsive max-width="280">
          <v-btn
            depressed
          >
            <nuxt-link to="#" class="text-decoration-none text-capitalize">
              Log in
            </nuxt-link>
          </v-btn>
          <nuxt-link to="#" class="text-decoration-none">
            <v-btn
              depressed
              color="primary"
              class="text-capitalize"
            >
              Create Account
            </v-btn>
          </nuxt-link>
        </v-responsive>
      </v-container>
    </v-col>
  </v-row>
</template>
