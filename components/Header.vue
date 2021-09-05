<template>
  <v-row no-gutters>
    <v-col
      cols="8"
      offset-md="2"
    >
      <v-container class="py-0 fill-height">
        <v-avatar
          color="black"
          size="48"
        >
          <v-icon size="46" class="white--text">
            mdi-dev-to
          </v-icon>
        </v-avatar>

        <!-- <v-btn
          v-for="link in links"
          :key="link"
          text
        >
          {{ link }}
        </v-btn> -->

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
            Log in
          </v-btn>
          <v-btn
            depressed
            color="primary"
          >
            Create Account
          </v-btn>
        </v-responsive>
      </v-container>
    </v-col>
  </v-row>
</template>
