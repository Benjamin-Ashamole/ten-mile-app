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
