<template>
  <v-container>
    <v-row justify="center">
      <v-col cols="12">
        <h1>This is a NuxtJS application that uses Typescript, Vuetify, Jest and SCSS.</h1>


        <v-row justify="center" class="mt-12">

          <v-col cols="12" md="8" lg="6">

            <v-card class="text-center mx-auto" max-width="600">


              <v-avatar width="125" height="125" class="mt-8">
                <v-img src="/img/default-user-image.png">

                </v-img>
              </v-avatar>

              <v-form class="px-4 py-8">
                <v-row justify="center">
                  <v-col cols="10" sm="12">
                    <v-text-field label="Username"/>
                  </v-col>
                  <v-col cols="10" sm="12">
                    <v-text-field label="Password"/>
                  </v-col>

                </v-row>
                <v-btn color="primary" class="mr-2">Login</v-btn>
                <v-btn color="white">Register</v-btn>

              </v-form>

            </v-card>
          </v-col>

        </v-row>
      </v-col>
    </v-row>

  </v-container>
</template>

<script>
    export default {}
</script>
