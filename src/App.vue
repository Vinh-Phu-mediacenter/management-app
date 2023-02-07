<template>
  <Home></Home>
  <v-icon name="bi-music-player" />
  <CoHamburgerMenu />
</template>

<script>
import Home from "./components/Home.vue";
import "./assets/tailwind.css";
import OhVueIcon from "oh-vue-icons";
import { CoHamburgerMenu } from "oh-vue-icons/icons";

export default {
  name: "App",
  components: {
    Home,
    "v-icon": OhVueIcon,
    CoHamburgerMenu,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
