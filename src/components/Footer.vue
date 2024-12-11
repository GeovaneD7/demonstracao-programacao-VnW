<script setup>
import logoCinza from "../assets/logo_cinza.png";
</script>

<template>
<footer>
  <ul>
    <li><a href="">Meus contatos</a></li>
    <li><a href="">LinkedIn</a></li>
    <li><a href="">GitHub</a></li>
  </ul>
  
  
  <div>
    <p>© 2024</p>
    <img :src="logoCinza" alt="">
  </div>
</footer>
</template>

<style scoped>
 footer {
  display: flex;
  align-items: center;
  justify-content: space-between;

  padding: 0 3vw;
  background-color: #12254D;
  color: #fff;
  height: 15vh;
  
  
  a { color:#fff;}

  img { width: 35%; }
  div {
    display: flex;
    align-items: center;
    flex-direction: row;
  }
 }
 
</style>
