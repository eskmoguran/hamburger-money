<template>
  <v-app>
    <SideMenu />
    <Header />
    <v-content><router-view /></v-content>
    <Footer />
  </v-app>
</template>

<script>
import Header from "./components/organisms/Header"
import Footer from "./components/organisms/Footer"
import SideMenu from "./components/organisms/SideMenu"

export default {
  name: "App",
  components: {
    Header,
    Footer,
    SideMenu
  }
};
</script>
