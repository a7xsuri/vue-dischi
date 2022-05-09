<template>
  <div id="app">
    <HeaderSpotify />
    <MainDischi />
  </div>
</template>

<script>
import HeaderSpotify from "./components/HeaderSpotify.vue";
import MainDischi from "./components/MainDischi.vue";
export default {
  name: "App",
  components: {
    HeaderSpotify,
    MainDischi,
  },
};
</script>

<style lang="scss">
@import "@/assets/style/general.scss";
@import "@/assets/style/vars.scss";
</style>