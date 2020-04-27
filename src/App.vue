<template>
  <div id="app">
    <div id="nav">
      <Nav/>
      <div class="nav-item">
      <button><router-link to="/">Home</router-link></button> |
      <button><router-link to="/news">News</router-link></button>
      </div>
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

.nav-item {
  padding-top: 12px;
  font-size: 20px;
  text-align: center;
  
}

a {
  text-decoration: none;
  color: white;
}

button {
  padding:5px 18px;
  background-color: rgb(204, 161, 243);
  border-radius: 5px;
}


</style>
