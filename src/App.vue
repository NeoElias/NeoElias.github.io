<template>
  <NavBar />

  <Home msg="Hey, it's me, Neo!" />
  <AboutMe />
  <MyProjects />
  <ContactMe />
  <Footer />
</template>

<script>
import Home from "./components/Home.vue";
import AboutMe from "./components/AboutMe.vue";
import NavBar from "./components/NavBar.vue";
import MyProjects from "./components/MyProjects.vue";
import ContactMe from "./components/ContactMe.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    NavBar,
    Home,
    AboutMe,
    MyProjects,
    ContactMe,
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
