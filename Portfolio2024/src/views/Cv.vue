<template>
    <div class="Cv">
      <h1>Mon CV</h1>
    </div>
    <main>
      <TheCv></TheCv>
    </main>
    
  </template>
  
  <style>
    .Cv{
      align-items: center;
      flex-grow:1;
      justify-content: center;
      font-size: 1rem;
      color: rgb(191, 106, 2);
    }
  
  </style>
  <script setup>
  import TheCv from '@/components/TheCv.vue'; 
  
  </script>
  