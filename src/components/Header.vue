<script setup>
import logo from "../assets/logo.png"
</script>

<template>
<nav>
  <img :src="logo" alt="">
  <ul>
    <li><a href="">Inicio</a></li>
    <li><a href="">Artigos</a></li>
  </ul>
</nav>
</template>

<style scoped lang="scss">
nav {
  display: flex;
  align-items: center;
  justify-content: space-between;

  height: 10vh;
  padding: 0 3vw;

  
  ul {
    display: flex;
    flex-direction: row;
  }
}

img {
  width: 3%;
}
</style>
