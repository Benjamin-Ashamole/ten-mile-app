<template>
  <div id="app">
    <div id="nav">
      <Nav/>
      <router-link to="/">Home</router-link> |
      <router-link to="/news">News</router-link>
    </div>
    <router-view />
  </div>
</template>

<script>
import Nav from "./components/layout/Nav.vue";
export default {
  name: "App",
  components: {
    Nav
  }
};
</script>

<style>

* {
  box-sizing: border-box;
  margin:0;
  padding:0;
}

html {
  height: 100%;
}

body {
  background-color: seashell;
  height:100%;
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}

</style>
