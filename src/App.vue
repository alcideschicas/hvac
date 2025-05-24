<script setup>
  import { RouterLink, RouterView } from 'vue-router'
  import Navbar from './components/Navbar.vue'
  import Hero from './components/Hero.vue'
  import Services from './components/Services.vue'
  import Team from './components/Team.vue'
  import Reviews from './components/Reviews.vue'
  import FAQ from './components/FAQ.vue'
  import Contact from './components/Contact.vue'
  import Footer from './components/Footer.vue'
</script>

<template>
  <div class="wrapper">
    <Navbar />
    <Hero />
    <Services />
    <Team />
    <Reviews />
    <FAQ />
    <Contact />
    <Footer />
  </div>
  <RouterView />
</template>