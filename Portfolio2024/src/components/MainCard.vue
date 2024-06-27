<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
    <div class="main-container">
        <div class='container-one'>
        </div>
        <div class="container-two">
            <RouterView />
        </div>
    </div>
</template>

<style scoped>
    img{
        height: 20px;
    }

    .link a{
        text-decoration: none;
        color: rgb(186, 84, 6);
        font: 10px;
    }
    
    .link img{
        height: 2rem;
    }
    .container-two{
        background-color: rgb(66, 133, 76);
        margin-left: 0%;
        width: 100%;
        border-radius: 2rem;
        padding: 0%;
        max-width: 1800px;
    }


    
    @media only screen and (max-width: 1800px){
        .main-container{
            width: 100%;
        }
        
    }
    
    @media (min-width: 1024px){}

</style>




