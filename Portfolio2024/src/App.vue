<script setup>


import MainCard from './components/MainCard.vue'
import MyMenu from './components/MyMenu.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <header>
    <MyMenu/>
  </header>
  <main>
    <MainCard/>
  </main>
  <Footer/>
</template>

<style scoped>
#app{background-color: black;}
</style>
