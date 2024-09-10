<template>
  <div id="app">
    <NavBar />
    <Intro />
    <AboutGravity />
    <MarketmakingComponent />
  </div>
</template>

<script>
import NavBar from "./components/NavBar";
import MarketmakingComponent from "./components/MarketmakingComponent";

import Intro from "./components/Intro";
import AboutGravity from "./components/AboutGravity";

export default {
  name: "App",
  components: {
    NavBar,
    Intro,
    AboutGravity,
    MarketmakingComponent,
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
