<template>
  <v-app>
    <v-app-bar app color="primary" dark></v-app-bar>

    <v-content>
      <Sidebar />
    </v-content>
  </v-app>
</template>

<script>
import Sidebar from "./components/Sidebar";

export default {
  name: "App",

  components: {
    Sidebar
  },

  data: () => ({
    //
  })
};
</script>
