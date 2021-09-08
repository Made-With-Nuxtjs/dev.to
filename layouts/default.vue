<template>
  <v-app>
    <v-navigation-drawer
      v-model="drawer"
      :clipped="clipped"
      fixed
      app
    >
      <v-card class="ma-3" :elevation="1">
        <h2 class="pa-2">
          <a href="#" class="text-decoration-none">DEV Community</a> is a
          community of 686,873 amazing developers
        </h2>
        <v-card-text>
          We're a place where coders share, stay up-to-date and grow their careers.
        </v-card-text>
        <nuxt-link to="#" class="text-decoration-none ">
          <div class="ma-3">
            <v-btn
              block
              depressed
              color="primary"
              class="text-capitalize"
            >
              Create new Account
            </v-btn>
          </div>
        </nuxt-link>

        <div class="text-center">
          <v-btn depressed class="text-capitalize">
            Log in
          </v-btn>
        </div>
      </v-card>
      <v-list flat tile>
        <div class="pl-5">
          <h4 class="text-capitalize">
            DEV Community
          </h4>
        </div>
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
    <v-app-bar
      :clipped-left="clipped"
      fixed
      app
      @click.stop=" !clipped"
    >
      <v-app-bar-nav-icon class="d-flex d-md-none" @click.stop="drawer = !drawer" />

      <Header class="d-none d-sm-flex" />
      <HeaderMobile class="d-flex d-sm-none" />
      <v-spacer />
    </v-app-bar>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>

    <v-footer
      :absolute="!fixed"
      app
    >
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  data () {
    return {
      clipped: true,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: 'mdi-apps',
          title: 'Home',
          to: '/'
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Sign In/Up',
          to: '/inspire'
        },
        {
          icon: 'mdi-post',
          title: 'Dev Post',
          to: '/post'
        },
        {
          icon: 'mdi-post',
          title: 'Listings',
          to: '/post'
        },
        {
          icon: 'mdi-post',
          title: 'Postcasts',
          to: '/post'
        },
        {
          icon: 'mdi-post',
          title: 'Videos',
          to: '/post'
        },
        {
          icon: 'mdi-post',
          title: 'Tags',
          to: '/post'
        },
        {
          icon: 'mdi-post',
          title: 'FAQ',
          to: '/post'
        },
        {
          icon: 'mdi-post',
          title: 'DEV Shop',
          to: '/post'
        },
        {
          icon: 'mdi-post',
          title: 'Sponsors',
          to: '/post'
        },
        {
          icon: 'mdi-post',
          title: 'About',
          to: '/post'
        },
        {
          icon: 'mdi-post',
          title: 'Contact',
          to: '/post'
        }
      ],
      right: false,
      title: 'Dev.to'
    }
  }
}
</script>
