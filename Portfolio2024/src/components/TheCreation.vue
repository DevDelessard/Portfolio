<script setup>
import { RouterLink, RouterView } from 'vue-router'
import TheCv from '../views/Cv.vue'
</script>

<template>
    <div id="All">
        <div class="title">
            <h1>Mes Creations
            </h1>
            <div class="technology-section">
                <div class="titre2">
                    <div class="media2">
                        <a href="#top"><img src="../assets/Mario.gif" alt="Profile picture" href="#top"></a>
                    </div>
                    <h2>Mon panel de Compétences</h2>
                </div>
            <div>
            <h2>Je suis en mesure de réaliser tous vos projets à l'aide de :</h2>
            </div>
            <div class="logo">
                <a href="https://developer.mozilla.org/fr/docs/Web/JavaScript" target="_blank" rel="noopener"><img src="../assets/javascript.png" alt="Javascript-logo"></a>
                <a href="https://developer.mozilla.org/fr/docs/Glossary/HTML5" target="_blank" rel="noopener"><img src="../assets/HTML.png" alt="Html-logo"></a>
                <a href="https://developer.mozilla.org/fr/docs/Web/CSS" target="_blank" rel="noopener"><img src="../assets/CSS.png" alt="Css-logo"></a>
            </div>
        </div>
        </div>
        <div class="ensemble">
            <div class="main1">
                <div class="projects-button1">
                    <nav>
                        <RouterLink tag="a" to="/Cv" >
                            Mon Cv
                            <a><img src="../assets/AperçuCv.PNG"></a>
                        </RouterLink>
                    </nav>
                </div>
            </div>
            <div class="main2">
                <div class="projects-button2">
                    <nav>
                        <a href="https://github.com/DevDelessard/Dynamiser-espace-commentaire.git"target="_blank" rel="noopener"> Espace de commentaire</a>
                    </nav>
                    <div>
                        <a href="https://github.com/DevDelessard/Dynamiser-espace-commentaire.git"target="_blank" rel="noopener"><img src="../assets/AperçuCom.PNG"></a>
                    </div>
                </div>
            </div>
        </div>
        <TheCv/>
    </div>
</template>

<style>
#All :hover{
        color: rgb(35, 7, 61);
        
    }
    .ensemble{
        display: flex inline;
        justify-content: center;
        
    }
    .main1{
        display: flex;
        flex-direction: column;
    }
    .main1 img{
        height: 20rem;
        width: 20rem;
        border-radius: 2em;
        border: 2px solid rgb(191, 106, 2);
        
    }
    .media2 img{
    display: flex;
    height: 10rem;
    }
    .projects-button1{
        display: flex;
        flex-direction: column;
        justify-content: center;
        margin-left: 30px;
        font-size: 2rem;
        font-weight: 500;
        border-radius: 2rem;
        transition: filter 0.3s ease;
        
    }
    .projects-button1:hover{
        box-shadow: 10px 10px 20px rgba(36, 36, 36, 0.5);
    }
    .projects-button2:hover{
        box-shadow: 10px 10px 20px rgba(36, 36, 36, 0.5);
    }

    .projects-button1 a{
        display: flex;
        flex-direction: column;
        justify-content: end;
        border-radius: 2rem;
    }
    .main2{
        display: flex;
        flex-direction: column;
        margin-left: 100px;
    }
    .main2 img {
        height: 20rem;
        width: 20rem;
        border-radius: 2em;
        border: 2px solid rgb(191, 106, 2);
        transition: filter 0.3s ease; 
    }
    .main2 img :hover{
        box-shadow: 10px 10px 20px rgba(36, 36, 36, 0.5);
    }
    .projects-button2{
        display: flex inline;
        flex-direction: column;
        justify-content: center;
        margin-left: 30px;
        font-size: 2rem;
        font-weight: 500;
        color: rgb(186, 84, 6);
        text-decoration: none;
        border-radius: 2rem;
        transition: filter 0.3s ease;
    }
    .projects-button1 a{
        text-decoration: none;
        color: rgb(186, 84, 6)
    }
    .projects-button2 a{
        text-decoration: none;
        color: rgb(186, 84, 6)
    }
</style>