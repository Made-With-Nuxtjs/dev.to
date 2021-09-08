<template>
  <v-container>
    <v-row justify="space-around">
      <v-card width="auto">
        <v-img
          height="200px"
          src="https://cdn.pixabay.com/photo/2020/07/12/07/47/bee-5396362_1280.jpg"
        >
          <v-card-title class="white--text mt-8">
            <v-avatar size="56">
              <img
                alt="user"
                src="https://cdn.pixabay.com/photo/2020/06/24/19/12/cabbage-5337431_1280.jpg"
              >
            </v-avatar>
            <p class="ml-3">
              David Joe
            </p>
          </v-card-title>
        </v-img>

        <v-card-text>
          <v-card flat class="font-weight-bold mb-2">
            <nuxt-link to="#" class="text-decoration-none ">
              <v-card flat class="ma-3">
                <v-btn
                  block
                  depressed
                  color="primary"
                  class="text-capitalize"
                >
                  Follow
                </v-btn>
              </v-card>
            </nuxt-link>
          </v-card>

          <v-card flat>
            <span class="pb-2"> Making databases fun @Prisma | Learning, building & Teaching | Quirky</span>
            <h4 class="text-uppercase">
              Location
            </h4>
            <span> http://localhost:3000 </span><span>🌍</span>

            <h4 class="text-uppercase">
              Work
            </h4>
            <span>Developer Advocate at Prisma</span>
            <h4 class="text-uppercase">
              Joined
            </h4>
            <span>  Mar 27, 2019</span>
          </v-card>
        </v-card-text>
      </v-card>
      <v-card width="400px" class="mt-5" :class="{ 'on-hover': hover }">
        <v-card-text>
          <v-card flat>
            <h2>
              More From
              <nuxt-link to="#" class="text-decoration-none pl-2 ">
                David Joe
              </nuxt-link>
            </h2>
          </v-card>

          <v-card flat class="py-3">
            <nuxt-link to="#" class="text-decoration-none">
              <h3 class="text--secondary">
                NoCode Platform with React.
              </h3>
            </nuxt-link>

            <nuxt-link to="#" class="text-decoration-none">
              <span>#beginners</span>
            </nuxt-link>
            <nuxt-link to="#" class="text-decoration-none">
              <span>#beginners</span>
            </nuxt-link>
            <nuxt-link to="#" class="text-decoration-none">
              <span>#beginners</span>
            </nuxt-link>
          </v-card>
          <v-divider />
          <v-card flat class="py-3">
            <nuxt-link to="#" class="text-decoration-none">
              <h3 class="text--secondary">
                NoCode Platform with React.
              </h3>
            </nuxt-link>

            <nuxt-link to="#" class="text-decoration-none">
              <span>#beginners</span>
            </nuxt-link>
            <nuxt-link to="#" class="text-decoration-none">
              <span>#beginners</span>
            </nuxt-link>
            <nuxt-link to="#" class="text-decoration-none">
              <span>#beginners</span>
            </nuxt-link>
          </v-card>
          <v-divider />
          <v-card flat class="py-3">
            <nuxt-link to="#" class="text-decoration-none">
              <h3 class="text--secondary">
                NoCode Platform with React.
              </h3>
            </nuxt-link>

            <nuxt-link to="#" class="text-decoration-none">
              <span>#beginners</span>
            </nuxt-link>
            <nuxt-link to="#" class="text-decoration-none">
              <span>#beginners</span>
            </nuxt-link>
            <nuxt-link to="#" class="text-decoration-none">
              <span>#beginners</span>
            </nuxt-link>
          </v-card>
        </v-card-text>
      </v-card>
    </v-row>
  </v-container>
</template>
