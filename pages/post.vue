<template>
  <v-row justify="center">
    <v-col>
      <v-card class="mx-auto px-8 " max-width="100%">
        <v-img src="https://picsum.photos/350/165?random" height="auto" />
        <v-row>
          <div class="pa-2 pt-8">
            <h1>
              18 amazing 🤩 GitHub repositories that will help you 🪄 make a
              Beautiful Project
            </h1>
          </div>

          <div class="text-center">
            <v-chip class="ma-2" label>
              <small>#<span>wedev2</span>
              </small>
            </v-chip>

            <v-chip class="ma-2" color="pink" label text-color="white">
              =
              <small>#<span>wedev3</span>
              </small>
            </v-chip>

            <v-chip class="ma-2" color="primary" label>
              <small>#<span>wedev4</span>
              </small>
            </v-chip>

            <v-chip class="ma-2" color="cyan" label text-color="white">
              <small>#<span>wedev5</span>
              </small>
            </v-chip>
          </div>

          <v-col cols="12">
            <span class="pr-4 ma-0 float-start">
              <v-avatar size="35">
                <img src="/pp.jfif" alt="John">
              </v-avatar>
            </span>

            <a href="#" class="black--text">
              <h5 class="font-weight-bold">David Cumix</h5>
            </a>

            <span class="caption">
              {{ new Date() }}
            </span>

            <span class="caption"> 14 min read </span>
          </v-col>
        </v-row>
        <!-- --- -->
        <h1 class="pt-10">
          Introduction
        </h1>
        <p>
          Today I would like to give examples of good GitHub repositories that will help you implement complex animations, as well as useful functions in your projects.
          Today I would like to give examples of good GitHub repositories that will help you implement complex animations, as well as useful.
          Today I would like to give examples of good GitHub repositories that will help you implement complex animations.
        </p>
        <span class="pt-8">So let's get started</span>
      </v-card>
      <PostBottomNav />
    </v-col>
    <v-col cols="3" sm="12" md="3" lg="3">
      <PostPageRight />
    </v-col>
  </v-row>
</template>

<script>
export default {
  data: () => ({
    bars: [
      { class: '' },
      { class: '', dark: true },
      { class: 'primary', dark: true },
      { class: 'elevation-0' }
    ]
  })
}
</script>
