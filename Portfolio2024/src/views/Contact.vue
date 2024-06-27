<template>
    <div class="Contact">
        <h1>Formulaire de Contact</h1>
    </div>
    <main>
        <ContactForm></ContactForm>
    </main>
    </template>
    
    <style>
        .Contact{
            align-items: center;
            flex-grow:1;
            justify-content: center;
            font-size: 1rem;
            color: rgb(191, 106, 2);
        }
    </style>
    <script setup>
    import ContactForm from '@/components/ContactForm.vue'; 
    </script>