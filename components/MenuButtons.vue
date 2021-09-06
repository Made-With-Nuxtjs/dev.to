<template>
  <v-card flat>
    <v-tabs
      color="deep-purple accent-4"
      right
    >
      <v-toolbar-title><h3>Posts</h3></v-toolbar-title>
      <v-spacer />
      <v-tab>Feed</v-tab>
      <v-tab>Week</v-tab>
      <v-tab>Year</v-tab>
      <v-tab>Month</v-tab>
      <v-tab>Infinity</v-tab>
      <v-tab>Latest</v-tab>

      <v-tab-item>
        <v-container>
          <Feed />
        </v-container>
      </v-tab-item>
      <v-tab-item>
        <v-container>
          <Week />
        </v-container>
      </v-tab-item>
      <v-tab-item>
        <v-container>
          <v-row>
            <v-col
              v-for="i in 6"
              :key="i"
              cols="12"
              md="4"
            >
              <v-img
                :src="`https://picsum.photos/500/300?image`"
                aspect-ratio="1"
              />
            </v-col>
          </v-row>
        </v-container>
      </v-tab-item>
      <v-tab-item>
        <v-container>
          <v-row>
            <v-col
              v-for="i in 6"
              :key="i"
              cols="12"
              md="4"
            >
              <v-img
                :src="`https://picsum.photos/500/300?image`"
                aspect-ratio="1"
              />
            </v-col>
          </v-row>
        </v-container>
      </v-tab-item>
      <v-tab-item>
        <v-container>
          <v-row>
            <v-col
              v-for="i in 6"
              :key="i"
              cols="12"
              md="4"
            >
              <v-img
                :src="`https://picsum.photos/500/300?image`"
                aspect-ratio="1"
              />
            </v-col>
          </v-row>
        </v-container>
      </v-tab-item>
      <v-tab-item>
        <v-container>
          <v-row>
            <v-col
              v-for="i in 6"
              :key="i"
              cols="12"
              md="4"
            >
              <v-img
                :src="`https://picsum.photos/500/300?image`"
                aspect-ratio="1"
              />
            </v-col>
          </v-row>
        </v-container>
      </v-tab-item>
    </v-tabs>
  </v-card>
</template>
