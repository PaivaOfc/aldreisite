<script setup lang="ts">
import Footer from '../components/Home/Footer.vue';
import About from '../components/Home/About.vue';
import Hero from '../components/Home/Hero.vue';
import NavBar from '../components/Home/NavBar.vue'
</script>


<template>
    <div class="min-h-screen font-sans text-brand-dark">
        <NavBar />
        <main>
            <Hero />
            <About />
        </main>
        <Footer />
    </div>
</template>