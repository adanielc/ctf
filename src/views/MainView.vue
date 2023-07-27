<template>
  <Main />
</template>

<script>
import { defineComponent } from "vue";

// Components
import Main from "../components/Main.vue";

export default defineComponent({
  name: "MainView",

  components: {
    Main,
  },
});
</script>
