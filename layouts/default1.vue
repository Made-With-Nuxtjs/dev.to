<template>
  <v-app>
    <v-navigation-drawer :clipped="clipped" fixed app>
      <v-card
        class="mx-auto"
        max-width="344"
        outlined
      >
        <v-list-item>
          <v-list-item-content>
            <h2 class="pa-2">
              <a href="#">DEV Community</a> is a
              community of 686,873 amazing developers
            </h2>
            <v-list-item-subtitle>Greyhound divisely hello coldly fonwderfully</v-list-item-subtitle>
          </v-list-item-content>
        </v-list-item>

        <v-card-actions>
          <v-btn
            outlined
            rounded
            text
          >
            Button
          </v-btn>
        </v-card-actions>
      </v-card>

      <v-list>
        <v-list-item
          v-for="(item, i) in items"
          :key="i"
          :to="item.to"
          router
          exact
        >
          <v-list-item-action>
            <v-icon>{{ item.icon }}</v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-title v-text="item.title" />
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
    <v-app-bar :elevation="1" :clipped-left="clipped" fixed app>
      <v-app-bar-nav-icon class="ml-3 mt-3" @click.stop="drawer = !drawer" />
      <Header class="d-none d-sm-flex" />
      <HeaderMobile class="d-flex d-sm-none" />
    </v-app-bar>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
    <v-footer :absolute="!fixed" app>
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  data () {
    return {
      drawer: false,
      clipped: false,
      fixed: false,
      items: [
        {
          icon: 'mdi-apps',
          title: 'Welcome',
          to: '/'
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Inspire',
          to: '/inspire'
        }
      ],

      title: 'Vuetify.js'
    }
  }
}
</script>
