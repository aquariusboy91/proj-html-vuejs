<template>
  <div id="app">
    <Header />
    <Jumbo />
    <UnderJambo />
    <Main />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Jumbo from "./components/Jumbo.vue";
import UnderJambo from "./components/UnderJambo.vue";
import Main from "./components/Main.vue";

export default {
  name: "App",
  components: {
    Header,
    Jumbo,
    UnderJambo,
    Main,
  },
};

</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap";
@import url('https://fonts.googleapis.com/css2?family=Libre+Franklin:wght@300;400&family=Roboto+Slab:wght@300&display=swap');

// #app {
//   font-family: Avenir, Helvetica, Arial, sans-serif;
//   -webkit-font-smoothing: antialiased;
//   -moz-osx-font-smoothing: grayscale;
//   text-align: center;
//   color: #2c3e50;
//   margin-top: 60px;
// }
</style>
