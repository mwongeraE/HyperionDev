<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="6" md="6" lg="6" xl="3">
    <v-card>
      <v-card class="logo py-4 d-flex justify-center elevation-0">
        
        <v-card-text>
      <v-row align="center">
        <v-col  cols="4">
          <Green />
        </v-col>
        <v-col
          class=""
          cols="8"
        >

        <v-card-title class="text-h6 text-md-h6 text-caption black--text">
          Web Development Bootcamp Trial
        </v-card-title>

          <v-card-actions>
          <v-btn
            color="custom-color-one"
            nuxt
            block
            to="/inspire"
            class="white--text"
          >
            Continue your trial

            <v-icon dark>
              mdi-arrow-right
            </v-icon>

          </v-btn>
        </v-card-actions>
        </v-col>
        
      </v-row>
    </v-card-text>
      </v-card>

      <v-divider class="mr-5 ml-5"></v-divider>

      <v-card class="mt-5 elevation-0">
        <v-card-title class="headline">
          Your Progress (1/4 Complete)
        </v-card-title>
        <v-card-text>
          <v-row>

            <v-col cols="6" sm="6" md="6" lg="6" xl="3">
              <v-btn
            color="custom-color-one"
            nuxt
            to="/inspire"
            block
            class="white--text"
          >
            Industry Knowledge 1

            <v-icon dark>
              mdi-check
            </v-icon>
          </v-btn>

            </v-col>

            <v-col cols="6" sm="6" md="6" lg="6" xl="3">
              <v-btn
            color="white"
            nuxt
            to="/inspire"
            block
            outlined
            class="custom-color-one--text"
          >
            Industry Knowledge 2
          </v-btn>
            </v-col>

          </v-row>

          <v-row justify="center">

            <v-col cols="6" sm="6" md="6" lg="6" xl="3">
              <v-btn
            color="white"
            nuxt
            to="/inspire"
            block
            outlined
            class="custom-color-one--text"
          >
            Html basics
          </v-btn>
            </v-col>

            <v-col cols="6" sm="6" md="6" lg="6" xl="3">
              <v-btn
            color="white"
            nuxt
            to="/inspire"
            block
            outlined
            class="custom-color-one--text"
          >
            Your first php script
          </v-btn>
            </v-col>

          </v-row>
        </v-card-text>
      </v-card>
    </v-card>

      <v-row class="ml-5 mt-6 caption">
         <h2 >
          Trial another bootcamp
        </h2>
      </v-row>

      <v-row class="mt-5">


        <v-col cols="6" sm="6" md="6" lg="6" xl="3">
          <v-card class="elevation-1">
            <v-row>
            <v-col cols="4" sm="4" md="4" lg="4" xl="4">
              <Software />
            </v-col>
            <v-col cols="8" sm="8" md="8" lg="8" xl="8">
              <Mobileboot />
            </v-col>
            </v-row>
          </v-card>
        </v-col>
        <v-col cols="6">
          <v-card class="elevation-1">
            <v-row>
            <v-col  cols="4" sm="4" md="4" lg="4" xl="4">
              <Mobile />
            </v-col>
            <v-col cols="8" sm="8" md="8" lg="8" xl="8">
             <Mobileboot />
            </v-col>
            </v-row>
          </v-card>
        </v-col>
      </v-row>
    </v-col>

    <v-col cols="12" sm="6" md="6" lg="6" xl="6">
      <v-card class="mt-5 elevation-0">
        <v-card-title class="headline">
          Your Coding Journey
          <v-icon>mdi-help-circle-outline</v-icon>
        </v-card-title>
        <v-card-text>
      <v-row align="center">
        <v-col
          class="text-h4 custom-color-one--text"
          cols="1" sm="1" md="1" lg="1" xl="1"
        >
          1
        </v-col>
        <v-col 
        cols="10" sm="10" md="10" lg="10" xl="6"
        class="text-h5 grey--text"
        >
        Total programs written
        </v-col>
      </v-row>
      <v-row align="center">
        <v-col
          class="text-h4 custom-color-one--text"
          cols="1" sm="1" md="1" lg="1" xl="1"
        >
          4
        </v-col>
        <v-col 
        cols="10" sm="10" md="10" lg="10" xl="6"
        class="text-h5 grey--text"
        >
        Total code reviews
        </v-col>
      </v-row>
    </v-card-text>
      </v-card>

      <v-divider class="mr-5 ml-5"></v-divider>

      <v-card class="mt-5 elevation-0">
        <v-card-title class="headline">
          Get More Information
        </v-card-title>
        <v-card-text>
          <v-row justify="center">

            <v-col cols="12" class="grey--text">
              We're ready to help with any questions you may have about our bootcamps and mentor support
            </v-col>

          </v-row>

          <v-row justify="start">

            <v-col cols="4">
              <v-btn
            color="white"
            nuxt
            to="/inspire"
            block
            outlined
            class="custom-color-one--text"
          >
            Book a call
          </v-btn>
            </v-col>

            <v-col cols="6">
              <v-btn
            color="white"
            nuxt
            to="/inspire"
            block
            outlined
            class="custom-color-one--text"
          >
            Join an info session
          </v-btn>
            </v-col>

          </v-row>
        </v-card-text>
      </v-card>

      <v-divider class="mr-5 ml-5"></v-divider>

      <v-card class="mt-5 elevation-0">
        <v-card-title class="headline">
          Upgrade to the full bootcamp
        </v-card-title>
        <v-card-text>
          <v-row justify="center">

            <v-col cols="12" class="grey--text">
             Our next cohort start 3 January 2018
            </v-col>

          </v-row>

          <v-row justify="start">

            <v-col cols="6">
              <v-btn
            color="white"
            nuxt
            to="/inspire"
            block
            outlined
            class="custom-color-one--text"
          >
            Reserve your spot
          </v-btn>
            </v-col>

          </v-row>
        </v-card-text>
      </v-card>
    </v-col>
  </v-row>
</template>
