<template>
    <head>
        <title>Mi Portafolio - Diseñador y Desarrollador Web</title>
        <meta name="description"
            content="Descubre mi portafolio de proyectos web, diseño y desarrollo. Conoce mis habilidades y servicios como diseñador y desarrollador web.">
        <meta name="keywords" content="portafolio, diseño web, desarrollo web, proyectos, diseñador, desarrollador">
    </head>
    <div>
        <Navbar />
        <HeroSection />
        <AboutMe />
        <Projects />
        <Contact />
        <NuxtPage />
    </div>
</template>

<script setup>
import Navbar from '~/components/Navbar.vue'
import HeroSection from '~/components/HeroSection.vue';
import AboutMe from '~/components/AboutMe.vue';
import Projects from '../components/Projects.vue';
import Contact from '~/components/Contact.vue';
</script>

<style scoped></style>