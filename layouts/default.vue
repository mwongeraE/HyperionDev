<template>
  <v-app >
    <div>
    <v-app-bar
      color="white"
      dense
      elevation="0"
    >
      <HyperLogo />

      <v-toolbar-title class="ml-6 text-h6 text-md-h6 text-caption black--text" v-if="mobile">Get Mentor support</v-toolbar-title>
        <!-- Else use long heading -->
      <v-toolbar-title class="ml-6 text-h6 text-md-h6 text-caption" v-else>Fullstack Web Developer Bootcamp</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-menu
        bottom
        min-width="200px"
        offset-y
      >
        <template v-slot:activator="{ on }">
          <v-btn
            icon
            x-large
            v-on="on"
            width="100px"
          >
          <v-row >
            <v-avatar
              color="brown"
              size="32"
            >
              <img
              src="https://cdn.vuetifyjs.com/images/john.jpg"
              lazy-src="https://cdn.vuetifyjs.com/images/john.jpg"
              srcset="https://cdn.vuetifyjs.com/images/john.jpg 600w,
              https://cdn.vuetifyjs.com/images/john.jpg 960w,
              https://cdn.vuetifyjs.com/images/john.jpg 1264w,
              https://cdn.vuetifyjs.com/images/john.jpg 1904w,
              https://cdn.vuetifyjs.com/images/john.jpg 2400w"
              alt="John"
              >
            </v-avatar>
            <p class="ma-2 text-md-body-1 text-caption"> profile </p>
          </v-row>
          </v-btn>
        </template>
        <v-card>
          <v-list-item-content class="justify-center">
            <div class="mx-auto text-center">
              <v-btn
                depressed
                rounded
                text
              >
                Edit Profile
              </v-btn>
              <v-divider class="my-3"></v-divider>
              <v-btn
                depressed
                rounded
                text
              >
                Logout
              </v-btn>
            </div>
          </v-list-item-content>
        </v-card>
      </v-menu>
    </v-app-bar>
  </div>


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
      clipped: false,
      drawer: false,
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
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'Vuetify.js',
      user: {
        initials: 'JD',
        fullName: 'John Doe',
        email: 'john.doe@doe.com',
      },
    }
  },
  computed: {
    mobile() {
      return this.$vuetify.breakpoint.xsOnly
    },
}
}
</script>

<style>

.v-toolbar__title {
  color: #f0571b;
}
.v-card__text {
  color: blue!important;
}
</style>
