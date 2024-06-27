<template>
    <div class="Creations">
        <h1>Mes Créations</h1>
    </div>
    <main>
        <TheCreation></TheCreation>
    </main>
    
</template>


<style>
    .Creations{
        align-items: center;
        flex-grow:1;
        justify-content: center;
        font-size: 1rem;
        color: rgb(191, 106, 2);
    }
</style>
<script setup>
import TheCreation from '@/components/TheCreation.vue'; 
</script>