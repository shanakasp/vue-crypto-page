<template>
  <div id="app">
    <NavBar />
    <Intro />
    <AboutGravity />
    <MarketmakingComponent />
    <M1 />
    <AboutCompany />
  </div>
</template>

<script>
import AboutGravity from "./components/AboutGravity";
import Intro from "./components/Intro";
import MarketmakingComponent from "./components/MarketmakingComponent";
import NavBar from "./components/NavBar";
import M1 from "./components/SecondIntro.vue";

import AboutCompany from "./components/AboutCompanySite.vue";

export default {
  name: "App",
  components: {
    NavBar,
    Intro,
    AboutGravity,
    MarketmakingComponent,
    M1,
    AboutCompany,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: black; /* Set the background color to black */
  min-height: 100vh; /* Ensure the background covers the entire viewport height */
  margin: 0;
  padding: 0;
}
</style>
