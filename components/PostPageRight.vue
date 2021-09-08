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
          <div class="font-weight-bold mb-2">
            <nuxt-link to="#" class="text-decoration-none ">
              <div class="ma-3">
                <v-btn
                  block
                  depressed
                  color="primary"
                  class="text-capitalize"
                >
                  Follow
                </v-btn>
              </div>
            </nuxt-link>
          </div>

          <div>
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
          </div>
        </v-card-text>
      </v-card>
      <v-card width="400px" class="mt-5">
        <v-card-text>
          <div class="pb-4">
            <h2>
              More From
              <nuxt-link to="#" class="text-decoration-none pl-2 ">
                David Joe
              </nuxt-link>
            </h2>
          </div>

          <div class="pb-3">
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
          </div>
          <v-divider />
          <div class="py-3">
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
          </div>
          <v-divider />
          <div class="py-3">
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
          </div>
        </v-card-text>
      </v-card>
    </v-row>
  </v-container>
</template>
