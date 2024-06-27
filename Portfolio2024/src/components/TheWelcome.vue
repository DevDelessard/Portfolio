<script setup>

import ContactForm from './ContactForm.vue'
</script>

<template>
  <div class="presentation">
    <div class="titre1">
      <div class="media1">
        <a href="#top"><img src="../assets/Toad.gif" alt="Profile picture"></a>
      </div>
    <h1> Bienvenue sur le Portfolio de Charles DELESSARD !</h1> 
    </div>
    <div class="texte">
      J'ai 31 ans, je suis developpeur Web Junior et j'utilise le framework VueJS pour vous montrer mon savoir faire.
    </div>
  </div>
  <div id="All">
        <div class="title">
            <h1>Mes Creations
            </h1>
            <h2>Une partie des projets sur lesquels j'ai travaillé</h2>
        </div>
        <div class="ensemble">
            <div class="main1">
              <div class="projects-button1">
                <RouterLink tag="a" to="/TheCreation" >
                Mon Cv
                <a href="#top"><img src="../assets/AperçuCv.PNG"></a>
                </RouterLink>
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
    </div>
    <ContactForm/>
</template>

<style>
  .presentation h1{
    font-size: 3rem;
  }
  .titre1{
    display: flex;
    justify-content: center;
    padding-right: 10rem;
    align-items: center;
  }
  .titre2{
    display: flex;
    justify-content: center;
    padding-right: 10rem;
    align-items: center;
  }
  .link a{
    text-decoration: none;
    color: rgb(186, 84, 6);
    font: 10px;
  }
  .link img{
    height: 2rem;
  }

  .logo{
    display: flex;
    justify-content: center;
    padding-top: 2rem;
    padding-bottom: 2rem;
  }
  .logo img{
        height: 5rem;
    }
  .texte{
    font-size: 1.5rem;
  }
  .media1 img{
    display: flex;
    height: 10rem;
    
  }
  .media2 img{
    display: flex;
    height: 10rem;
  }
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
        border-radius: 2rem;
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
    }
    .main2{
        display: flex;
        flex-direction: column;
        margin-left: 100px;
        margin-bottom: 30px;
    }
    .main2 img {
        height: 20rem;
        width: 20rem;
        border-radius: 2rem;
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
    .ContactForm{
      display: flex;
      margin-top: 20px;
    }
</style>