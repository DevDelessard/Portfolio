<script setup>

</script>

<template>
    <div class="main-menu" >
        <div class="title">
            <a href="#top"><img src="https://icones.pro/wp-content/uploads/2022/07/symbole-de-la-planete-terre-vert.png" alt="Profile picture"></a>
            <h1>Portfolio</h1>
        </div>
        <div class="menu">
            <!--<div class="presentation">
                <a href="" target="_blank">Accueil</a>
            </div>
            <div class="creations">
                <a href="/TheCv.vue" target="_blank">Créations</a>
            </div>
            <div class="contact">
                <a href="" target="_blank">Contact</a>
            </div>-->
            <div class="button-container">
                <div class="projects-button">
                    <nav>
                        <RouterLink to="/">Présentation</RouterLink>
                    </nav>
                </div>
                <div class="projects-button">
                    <nav>
                        <RouterLink to="/TheCreation">Créations</RouterLink>
                    </nav>
                </div>
                <div class="projects-button">
                    <nav>
                        <RouterLink to="/Contact">Contact</RouterLink>
                    </nav>
                </div>
                    <div class="projects-button">
                    <nav>
                        <RouterLink to="/TheError">En savoir plus</RouterLink>
                    </nav>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>

    .main-menu{        
        display: flex;
        justify-content: center;
        background-color: rgb(69, 2, 60);
        border-radius: 25px;
        padding: 0%;
        margin-top: 0.5%;
        width: 100%;
        height: 4rem;
        position: fixed;
        top: 0;
        max-width: 1800px;
        
    }
    .title{
        display: flex;
        align-items: center;
        flex-grow:1;
        justify-content: center;
        font-size: 1.5rem;
        color: rgb(191, 106, 2);
        
    }

    .title h1{
        display: flex;
        margin: 20%;

    }

    .menu{
        display: flex;
        flex-direction: row;
        flex-grow: 1.5;
        justify-content: space-between;
        font-size: 1.3rem;
        color: rgb(191, 106, 2);
        
    }
    .button-container{
        margin-top: 0.5%;
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;

    }
    .projects-button{
        background-color: rgb(191, 106, 2);
        border-radius: 2rem;
        padding: 5px;
        margin: 5px;
    }
    #projects-button:active{
        text-decoration: underline;
    } /*ça ne marche pas - Probablement du au Router*/

    .projects-button2{
        background-color: rgb(191, 106, 2);
        border-radius: 2rem;
        padding: 5px;
        margin: 5px;
    }
    .projects-button3{
        background-color: rgb(191, 106, 2);
        border-radius: 2rem;
        padding: 5px;
        margin: 5px;
    }
    .projects-button4{
        background-color: rgb(191, 106, 2);
        border-radius: 2rem;
        padding: 5px;
        margin: 5px;
    }
    .projects-button a{
        text-decoration: none;
    }
    .title img{
        display: flex;
        height: 5rem;
        border-radius: 50%;
        padding: 0%;
    }

</style>

