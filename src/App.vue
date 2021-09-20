<template>
  <base-header />
  <home-page />
  <base-footer />
</template>


<script>
import HomePage from "./components/HomePage.vue";
import BaseHeader from "./components/BaseHeader.vue";
import BaseFooter from "./components/BaseFooter.vue";
export default {
  name: "App",
  components: {
    HomePage,
    BaseHeader,
    BaseFooter,
  },
};
</script>

<style>
body {
  margin: 0;
  font-family: "Merienda", Helvetica, Arial;
}
</style>

    HomePage