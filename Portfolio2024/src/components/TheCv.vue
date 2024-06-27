<script setup>

</script>

<template>
<div class="body1">
    <header>
        <br>
        <img src="https://i.ibb.co/5hLDYYV/Photo-de-profil.jpg" alt="Photo de profil" id="profil">
        <h1>CHARLES DELESSARD</h1>
        <p>Developpeur web junior</p>
    </header>
    <address>
        <a href="https://www.google.fr/maps/place/15+Rue+des+Fleurs,+73190+Challes-les-Eaux/@45.5505071,5.9746585,15z/data=!3m1!4b1!4m5!3m4!1s0x478baee68f514235:0xfc493b7bce12b3ec!8m2!3d45.5504925!4d5.9849368?entry=ttu" style="color:white">15 Rue des fleurs <br>73190 Challes-les-Eaux</a>
        <a href="mailto:devdelessard@gmail.com" style="color:white">devdelessard@gmail.com</a>
        <a href="tel:0606060606" style="color:white">0606060606</a>
    </address>
    <main>
        <section id="Section1">
            <h2>A propos</h2>
                <p id="p2" >Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae nesciunt doloribus voluptatum alias delectus, incidunt veritatis, quaerat amet autem quae rerum eos unde rem tempore sit quasi pariatur exercitationem atque?</p>
            <h2>Langues parlées</h2>
            <ul>
                <li>Français - Langue maternelle</li>
                <li>Anglais - Intermédiaire</li>
                <li>Espagnol - Débutant</li>
            </ul>
            <h2>Centres d'Interêt</h2>
            <ul>
                <li>Ski</li>
                <li>Hockey</li>
                <li>Jeux-vidéos</li>
                <li>...</li>
            </ul>
        </section>
        <section id="Section2">
            <h2>Expériences professionnelles</h2>
            <h3>Technicien SAV Climatisation - Chauffage et clim du Val Gelon (73)</h3>
            <p>Du 1/10/2022 au 1/10/2024</p>
            <ul>
                <li>Diagnostic & Dépannage de climatisations</li>
                <li>Diagnostic & Dépannage de Pompes à chaleur </li>
                <li>Entretien de Climatisations</li>
                <li>Entretien de Pompes à chaleur</li>
            </ul>
            <h3>Chargé d'affaires Chauffage et Climatisation - Oxalli (73)</h3>
            <p>Du 01/07/2019 au 30/09/2022</p>
            <ul>
                <li>Elaboration d'études thermiques et hydrauliques</li>
                <li>Conception de plans sur Autocad/Plancal</li>
                <li>Réalisation de devis et dossiers techniques/administratifs</li>
                <li>Gestion des plannings & Management</li>
                <li>Négociations et commandes des matériaux, approvisionnement</li>
                <li>Suivi de chantiers</li>
            </ul>
            <h2>Diplômes/Formations</h2>
            <h3>Formation Developpeur Web</h3>
            <p>Du 30/01/2024 au 30/01/2025</p>
            <p>Centre Européen de formation</p>
            <h3>DUT Genie Thermique et Energies</h3>
            <p>Du 15/09/2016 au 30/06/2018</p>
            <p>IUT Cherbourg-Manche</p>
            <h2>Compétences</h2>
            <ul>
                <li>HTML5 - Expert</li>
                <li>CSS3 - Intermédiaire</li>
                <li>GitHub - Débutant</li>
            </ul>
        </section>
    </main>  
    <footer>
        <br>
        <div class="Linkfinal">
            <a href="https://www.linkedin.com/in/charles-delessard-b16957137?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3B4L3EvJP0Q0yYw%2ByfLb5nOA%3D%3D" target="_blank"><img src="../assets/linkedin.png" alt="logo Linkedin" id="linkedin" height="40" width="40" ></a>
            <a href="https://twitter.com/?logout=1708985161041" target="_blank"><img src="../assets/twitter.png" alt="logo twitter" id="twitter" height="40" width="40"></a>
            <a href="https://github.com/DevDelessard/Portfolio.git" target="_blank"><img src="../assets/github.png" alt="logo GitHub" id="github" height="40" width="40"></a>
        </div>
        <p id="p1">Dernière mise à jour le 02/03/2024</p>
    </footer>
</div>
</template>

<style scoped>
.body1 {
    vertical-align: top;
    font-family: "Raleway", sans-serif;
    font-style: normal;
    margin-left: auto;
    margin-right: auto;
    width: 1160px;
    font-size: 1em;
    font-weight: 500;
    border-style: solid;
    border-width: medium;
    border-radius: 2rem;
    background-color: #ffffff;
}

h1{
    font-family:"lato",sans-serif;
    font-weight: 400;
    font-style: normal;
}

h2 {background-color:#dbc2a4;
    
    font-family:"lato",sans-serif;
    font-weight: 400;
    font-style: normal;
    color: #000;
    padding: 0px 30px 0px 0px;
    text-indent: 20px;
    margin-right: 20px;
    font-weight: 900;
}

#profil {
    display: flex;
    flex-direction: row;
    width: 170px;
    height: 100%;
    object-fit: cover;
    border-radius: 50%;
    cursor: zoom-in;
    box-shadow:  -2px 1px 30px 2px #dbc2a4, 2px 2px 30px 2px #000 ;
}

header {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: auto;
    width: 1160px;
    color: white;
    font-size: 1em;
    background-color:#782221;
    border-top-right-radius: 25px;
    border-top-left-radius: 25px;
}
header p {
    font-size: 1.6em;
    font-weight: 500;
    font-family:"lato",sans-serif
}

address {display: flex;
    justify-content: center;
    justify-content: space-around;
    flex-direction: row;
    height: 80px;
    align-items: center;
    background-color:#2c1d27 ;
} A{text-decoration: none;}

main {
    display: flex;
    flex-direction:row;
    justify-content: center;
    justify-content: space-between;
    height: auto;
}
#Section1 {
    display: flex;
    flex-direction: column;
    width: 400px;
    height: 1100px;
    text-align: justify;
    color: white;
    background-color:#782221;
}
#Section2 {
    display: flex;
    flex-direction: column;
    width: 724px;
    height: 1100px;
    margin-left: 0px;
    margin-right: 0px;
    padding: 0px 0px 0px 0px;
}
#Section2 :hover{
    color: #6D071A;
}
#Section2 h2 {
    border-color: #782221;
    border-left-width: 10px;
    border-bottom-width: 0px;
    border-top-width: 0px;
    border-right-width: 0px;
    border-style: solid;
}
footer {
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    height: 100px;
    width: 1160px;
    background-color:#782221;
    border-bottom-left-radius: 25px;
    border-bottom-right-radius: 25px;
}

#p1{
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    color: white;
    font-size: 0.8em;
}
#p2 {text-indent: 100px;
    padding: 0px 20px 0px 20px;
}
h3 {font-size: 1em;
    font-weight: 900;
}


</style>