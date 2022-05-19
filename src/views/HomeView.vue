<template>
  <div class="home">
    <Menu />
    <div id="home" class="fondo home">hola soy home</div>
    <div id="about" class="fondo about">hola soy about</div>
    <div id="contact" class="fondo home">hola soy contact</div>
  </div>
</template>

<script>
import Menu from "../components/Menu.vue";

export default {
  name: "HomeView",
  components: {
    Menu,
  },
};
</script>
<style scoped>
.fondo {
  height: 100vh;
  color: azure;
}
.home {
  background-color: #bc1212;
}
.about {
  background-color: #12bc12;
}
</style>
