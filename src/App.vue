<template>
  <div id="app">
    <div class="container">
      <Header />
    </div>
    <Hero />
    <div class="container">
      <Features />
    </div>
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view /> -->
  </div>
</template>
<script>
import Header from "@/views/Header.vue";
import Hero from "@/views/Hero.vue";
import Features from "@/views/Features.vue";
export default {
  name: "app",
  components: {
    Header,
    Hero,
    Features,
  },
};
</script>
<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
.container {
  width: 90%;
  margin: 0 auto;
  max-width: 1000px;
}
// #nav {
//   padding: 30px;

//   a {
//     font-weight: bold;
//     color: #2c3e50;

//     &.router-link-exact-active {
//       color: #42b983;
//     }
//   }
// }
</style>
