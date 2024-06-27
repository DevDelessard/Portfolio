<script setup>
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <div class="Accueil">
    <h1>Présentation</h1>
  </div>
  <main>
    <TheWelcome />
  </main>
</template>

<style>
    .Accueil{
        align-items: center;
        flex-grow:1;
        justify-content: center;
        font-size: 1rem;
        color: rgb(191, 106, 2);
    }
</style>
