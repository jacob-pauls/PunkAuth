<template>
  <div>
    <Home />
    <router-view></router-view>
  </div>
</template>

<script>
import Home from './components/Home.vue'

export default {
  name: 'App',
  components: {
    Home
  }
}
</script>

<style>
/* Poppins */
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

/* Digestive */
@font-face {
  font-family: "Digestive";
  src: local("Digestive"),
   url(./fonts/Digestive.otf) format("truetype");
}
</style>
