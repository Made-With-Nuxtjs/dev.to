<template>
  <v-row justify="center">
    <v-card flat>
      <HomeTopNav />
    </v-card>

    <v-col cols="12" md="9" lg="9">
      <!-- /////////With-image card//////// -->

      <v-card
        v-for="img in 10"
        :key="img"
        class="mx-auto mb-3"
        width="auto"
      >
        <v-img
          src="https://picsum.photos/350/165?random"
          height="auto"
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
            <div class="pt-2">
              <h2>
                <nuxt-link to="/post" class="text-decoration-none black--text">
                  Top 10 VS Code Themes
                </nuxt-link>
              </h2>
            </div>
          </v-col>
        </v-row>
        <v-row
          align="center"
          class="ml-12"
        >
          <nuxt-link to="#" class="text-decoration-none text--secondary">
            <small
              v-for="chips in 5"
              :key="chips"
              class="pl-3"
            >#<span>wedev</span>
            </small>
          </nuxt-link>
        </v-row>
        <v-row
          align="center"
          class="ml-12 py-3 mb-3"
        >
          <nuxt-link to="#" class="text-decoration-none text--secondary">
            <div>
              <h5> <v-icon>mdi-heart-outline</v-icon><span class="px-2">1234</span> reactions</h5>
            </div>
          </nuxt-link>
          <v-spacer />

          <div class="mr-6">
            <span class="caption">
              14 min read
            </span>
            <span>
              <nuxt-link to="#" class="text-decoration-none">
                <v-btn depressed>
                  <span class=" font-weight-light">Save</span>
                </v-btn>
              </nuxt-link>
            </span>
          </div>
        </v-row>
      </v-card>
      <!-- /////////WithOUT-image card//////// -->

      <v-card
        v-for="n in 10"
        :key="n"
        class="mx-auto mb-3"
        max-width="100%"
      >
        <v-row flat dense no-gutters>
          <span class="pt-6 pl-5 pr-2 ma-0 float-end">
            <v-avatar size="35">
              <img
                src="/vuetify-logo.svg"
                alt="John"
              >
            </v-avatar>
          </span>
          <v-col cols="10">
            <div class="mt-4 d-flex">
              <a href="#" class="black--text">
                <h5 class="float-start font-weight-bold">David Jony</h5>
              </a>
            </div>

            <div class="d-flex">
              <span class="float-start caption">
                {{ new Date() }}
              </span>
            </div>
            <div class="pt-2">
              <h2>
                Best design 🎨 resources websites every developer 💻 should bookmark🔖
              </h2>
            </div>
          </v-col>
        </v-row>
        <v-row
          align="center"
          class="ml-12"
        >
          <nuxt-link to="#" class="text-decoration-none text--secondary">
            <small
              v-for="chip in 5"
              :key="chip"
              class="pl-3"
            >#<span>wedev</span>
            </small>
          </nuxt-link>
        </v-row>
        <v-row
          align="center"
          class="ml-12 py-3 mb-3"
        >
          <nuxt-link to="#" class="text-decoration-none text--secondary">
            <div>
              <h5> <v-icon>mdi-heart-outline</v-icon><span class="px-2">1234</span> reactions</h5>
            </div>
          </nuxt-link>
          <v-spacer />

          <div class="mr-6">
            <span class="caption">
              14 min read
            </span>
            <span>
              <nuxt-link to="#" class="text-decoration-none">
                <v-btn depressed>
                  <span class=" font-weight-light">Save</span>
                </v-btn>
              </nuxt-link>
            </span>
          </div>
        </v-row>
      </v-card>
    </v-col>

    <v-col cols="" sm="12" md="3" lg="3">
      <HomePageRight />
    </v-col>
  </v-row>
</template>
