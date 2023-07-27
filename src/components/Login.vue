<template>
  <v-container fluid class="fill-height">
    <v-row>
      <v-col class="justify-center">
        <v-row class="justify-center">
          <v-col cols="6" md="2">
            <v-text-field label="Username"></v-text-field>
          </v-col>
        </v-row>
        <v-row class="justify-center">
          <v-col cols="6" md="2">
            <v-text-field label="Password"></v-text-field>
          </v-col>
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>
<script>
export default {
  name: "Login",

  data: () => ({}),
};
</script>
