<template>
  <NavBar />
  <img alt="Profile Image" src="./assets/profile-pic.jpeg" />
  <Home msg="Hey, I'm Neo." />
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
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
