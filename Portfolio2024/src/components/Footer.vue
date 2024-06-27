<template>
<div class="mainfooter">
    <div class="social-links">
        <a href="https://github.com/DevDelessard/Portfolio.git " target="_blank">
            <div class="link">
                <img src="../assets/github.png" alt="GitHub logo">
            </div>
        </a>
        <a href="https://www.linkedin.com/in/charles-delessard-b16957137?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3B4L3EvJP0Q0yYw%2ByfLb5nOA%3D%3D" target="_blank">
            <div class="link">
                <img src="../assets/linkedin.png" alt="Linkedin logo">
            </div>
        </a>
        <a href="https://www.facebook.com/charles.delessard/" target="_blank">
            <div class="link">
                <img src="../assets/facebook.png" alt="Facebook logo">
            </div>
        </a>
    </div>
    <div>
        Dernière mise à jour le 13/06/2024
    </div>
</div>



</template>

<style>
    .mainfooter{
        display: flex;
        background-color: rgb(69, 2, 60);
        border-radius: 25px;
        flex-direction: column;
        justify-content: center;
        max-width: 1800px;
        height: 4.5rem;
        color: rgb(186, 84, 6);
        font-size: 1rem;
    }

    .social-links{
        display: flex;
        justify-content:  center;
        align-items: center;
    }

    .social-links a{
        display: flex;
        color: rgb(186, 84, 6);
        flex-direction: row;
        justify-content: center;
        width: 8rem;
    }

    .social-links a img{
        display: flex;
        width: 3rem;
        height: 3rem;


    }

</style>