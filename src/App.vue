<template>
  <v-app>
    <v-app-bar app clipped-left dark color="primary">
      <v-toolbar-title>VuePong</v-toolbar-title>
    </v-app-bar>
    <v-navigation-drawer app clipped dark class="secondary"></v-navigation-drawer>
    <v-content class="background noOverflow">
      <router-view />
    </v-content>
  </v-app>
</template>

<script>
export default {
  name: "App",
  data: () => ({
    //
  })
};
</script>
