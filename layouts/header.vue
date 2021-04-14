<template>
  <v-app-bar dense app>
    <v-toolbar-title v-text="title" />
    <v-row class="justify-end">
      <v-btn plain class="ma-0" v-for="menu in menus" :key="menu.name">
        {{ menu.name }}
      </v-btn>
    </v-row>
  </v-app-bar>
</template>

<script>
export default {
  data() {
    return {
      title: "Portfolio",
      menus: [
        {
          name: "Skills",
          url: "#"
        },
        {
          name: "Portfolio",
          url: "#"
        },
        {
          name: "Awards",
          url: "#"
        },
        {
          name: "Contact me",
          url: "#"
        },
        {
          name: "My Blog",
          url: "#"
        }
      ]
    };
  }
};
</script>

<style></style>
