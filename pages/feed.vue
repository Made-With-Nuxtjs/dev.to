<template>
  <v-row justify="center">
    <v-col cols="9" sm="12" md="9" lg="9">
      <v-card
        flat
      >
        <v-card
          v-for="n in 10"
          :key="n"
          class="mx-auto mb-3"
          max-width="100%"
        >
          <v-img
            src="https://picsum.photos/350/165?random"
            height="400px"
          />
          <v-row flat dense no-gutters>
            <span class="pt-6 pl-5 pr-2 ma-0 float-end">
              <v-avatar size="35">
                <img
                  src="/pp.jfif"
                  alt="John"
                >
              </v-avatar>
            </span>
            <v-col cols="10">
              <div class="mt-4 d-flex">
                <a href="#" class="black--text">
                  <h5 class="float-start font-weight-bold">David Cumix</h5>
                </a>
              </div>

              <div class="d-flex">
                <span class="float-start caption">
                  {{ new Date() }}
                </span>
              </div>
              <div>
                <h2>
                  Top 10 VS Code Themes
                </h2>
              </div>
              <div>
                span
              </div>
            </v-col>
          </v-row>

          <v-card-actions>
            <v-btn
              color="orange lighten-2"
              text
            >
              Explorefffffffffffffffff
            </v-btn>

            <v-spacer />

            <v-btn
              icon
              @click="show = !show"
            >
              <v-icon>mdi-dev-to</v-icon>
            </v-btn>
          </v-card-actions>
        </v-card>
      </v-card>
    </v-col>
  </v-row>
</template>
