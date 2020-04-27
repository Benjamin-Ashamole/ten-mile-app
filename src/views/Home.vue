<template>
  <div class="home">
    <home-button-component/>
  </div>
</template>

<script>
// @ is an alias to /src

import HomeButtonComponent from "../components/HomeComponent.vue"

export default {
  name: "Home",
  components: {
    HomeButtonComponent
  }
};
</script>

<style scoped>
  .home {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 100%;
    margin: auto;
  }
</style>