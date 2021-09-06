<template>
  <v-card>
    <v-tabs
      color="deep-purple accent-4"
    >
      <v-toolbar-title><h3>Posts</h3></v-toolbar-title>
      <v-spacer />
      <v-tab href="#feed">
        Feed
      </v-tab>
      <v-tab href="#week">
        Week
      </v-tab>
      <v-tab href="#month">
        Month
      </v-tab>
      <v-tab href="#year">
        Year
      </v-tab>
      <v-tab href="#infinity">
        Infinity
      </v-tab>
      <v-tab href="#latest">
        Latest
      </v-tab>

      <!-- <v-tab-items>
        <v-tab-item
          :value="'tab-1'"
        >
          <v-container>
            <v-row>
              <v-col
                v-for="i in 6"
                :key="i"
                cols="12"
                md="4"
              >
                <v-img
                  :src="`https://picsum.photos/500/300?image=${i * n * 5 + 10}`"
                  :lazy-src="`https://picsum.photos/10/6?image=${i * n * 5 + 10}`"
                  aspect-ratio="1"
                />
              </v-col>
            </v-row>
          </v-container>
        </v-tab-item>
      </v-tab-items> -->

      <v-tabs-items v-model="tab">
        <v-tab-item
          :value="'feed'"
        >
          <v-card flat>
            <v-card-text><h3>hhellll</h3></v-card-text>
          </v-card>
        </v-tab-item>
        <v-tab-item
          :value="week"
        >
          <v-card flat>
            <v-card-text><h3>hhellll</h3></v-card-text>
          </v-card>
        </v-tab-item>
        <v-tab-item
          :value="month"
        >
          <v-card flat>
            <v-card-text><h3>hhellll</h3></v-card-text>
          </v-card>
        </v-tab-item>
        <v-tab-item
          :value="feed"
        >
          <v-card flat>
            <v-card-text><h3>hhellll</h3></v-card-text>
          </v-card>
        </v-tab-item>
        <v-tab-item
          :value="feed"
        >
          <v-card flat>
            <v-card-text><h3>hhellll</h3></v-card-text>
          </v-card>
        </v-tab-item>
        <v-tab-item
          :value="feed"
        >
          <v-card flat>
            <v-card-text><h3>hhellll</h3></v-card-text>
          </v-card>
        </v-tab-item>
      </v-tabs-items>
    </v-tabs>
  </v-card>
</template>
