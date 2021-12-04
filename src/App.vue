<template>
  <NavBar />

  <Home msg="Neo" />
  <AboutMe />
  <MyProjects />
  <ToolKit />
  <Footer />
</template>

<script>
import Home from "./components/Home.vue";
import AboutMe from "./components/AboutMe.vue";
import NavBar from "./components/NavBar.vue";
import MyProjects from "./components/MyProjects.vue";
import ToolKit from "./components/ToolKit.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    NavBar,
    Home,
    AboutMe,
    MyProjects,
    ToolKit,
    Footer,
  },
};
</script>

<style>
html,
body {
  background-color: none;
}
</style>
