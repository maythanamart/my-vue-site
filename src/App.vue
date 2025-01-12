<template>
  <v-app>
    <v-app-bar app color="primary" dark>
      <v-toolbar-title>My Vue.js Website</v-toolbar-title>
    </v-app-bar>

    <v-main>
      <v-container>
        <v-row>
          <v-col cols="12" md="6">
            <v-card>
              <v-card-title>Welcome to My Portfolio</v-card-title>
              <v-card-text>
                This is a simple site built with Vue.js and Vuetify. Explore the components and features we offer!
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="6">
            <v-card>
              <v-img
                src="https://via.placeholder.com/300"
                alt="Placeholder Image"
                height="200"
              ></v-img>
              <v-card-title>Beautiful Designs</v-card-title>
              <v-card-text>
                Using Vuetify, creating responsive and attractive designs is easy and fun.
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
    </v-main>

    <v-footer app color="primary" dark>
      <v-container>
        <p class="text-center">© 2025 My Vue.js Website. All Rights Reserved.</p>
      </v-container>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
/* You can add custom CSS here */
</style>
