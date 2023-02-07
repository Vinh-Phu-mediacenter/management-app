<template>
  <HeaderApp></HeaderApp>
  <Navbar></Navbar>
</template>

<script>
import HeaderApp from "./Header.vue";
import Navbar from "./Navbar.vue";

export default {
  name: "Home-app",
  components: {
    HeaderApp,
    Navbar,
  },
  data() {
    return {};
  },
};
</script>
