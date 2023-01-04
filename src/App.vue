<template>
  <v-app>
    <v-app-bar :elevation="5" title="Vue3-Vuetify3 Demo Uppsetning"></v-app-bar>
    <v-main>
      <div id="nav" class ="mt-5 ml-5">
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link>
      </div>
    <router-view />
    </v-main>
    <v-footer border>Kristófer 2023</v-footer>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
}
</script>
