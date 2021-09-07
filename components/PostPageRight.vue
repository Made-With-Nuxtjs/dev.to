<template>
  <v-container>
    <v-row justify="space-around">
      <v-card width="400">
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
              John Doe
            </p>
          </v-card-title>
        </v-img>

        <v-card-text>
          <div class="font-weight-bold ml-8 mb-2">
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
          </div>

          <div>
            <span class="pb-2"> Making databases fun @Prisma | Learning, building & Teaching | Quirky</span>
            <h4>LOCATION</h4>
            <span> http://localhost:3000 </span><span>🌍</span>

            <h4>LOCATION</h4>
            <span>Developer Advocate at Prisma</span>
            <h4>JOINED</h4>
            <span>  Mar 27, 2019</span>
          </div>
        </v-card-text>
      </v-card>
      <v-speacher />
      <v-card width="400">
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
              John Doe
            </p>
          </v-card-title>
        </v-img>

        <v-card-text>
          <div class="font-weight-bold ml-8 mb-2">
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
          </div>

          <div>
            <span class="pb-2"> Making databases fun @Prisma | Learning, building & Teaching | Quirky</span>
            <h4>LOCATION</h4>
            <span> http://localhost:3000 </span><span>🌍</span>

            <h4>LOCATION</h4>
            <span>Developer Advocate at Prisma</span>
            <h4>JOINED</h4>
            <span>  Mar 27, 2019</span>
          </div>
        </v-card-text>
      </v-card>
    </v-row>
    </v-row>
  </v-container>
</template>
