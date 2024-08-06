<template>
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

<style scoped>

</style>