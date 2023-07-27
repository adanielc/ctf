<template>
  <v-layout>
    <v-app-bar :elevation="2" color="primary" prominent>
      <v-app-bar-nav-icon
        variant="text"
        @click.stop="drawer = !drawer"
      ></v-app-bar-nav-icon>
      <v-toolbar-title>CTF</v-toolbar-title>
    </v-app-bar>
    <v-navigation-drawer v-model="drawer" location="left" temporary>
      <v-list :items="items"></v-list>
    </v-navigation-drawer>
    <v-main style="height: 500px"> </v-main>
  </v-layout>
</template>

<script>
export default {
  name: "Main",

  data: () => ({
    drawer: false,

    items: [
      {
        title: "Foo",
        value: "foo",
      },
      {
        title: "Bar",
        value: "bar",
      },
      {
        title: "Fizz",
        value: "fizz",
      },
      {
        title: "Buzz",
        value: "buzz",
      },
    ],
  }),
};
</script>
