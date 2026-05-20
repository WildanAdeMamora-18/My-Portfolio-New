<script setup>
import Navbar from "./components/AppNavbar.vue";
import HeroSection from "./components/HeroSection.vue";
import AboutSection from "./components/AboutSection.vue";
import SkillsSection from "./components/SkillsSection.vue";
import ProjectSection from "./components/ProjectSection.vue";
import ContactSection from "./components/ContactSection.vue";
import AppFooter from "./components/AppFooter.vue";
</script>

<template>
  <div class="min-h-screen bg-slate-950 text-white overflow-hidden">
    <Navbar />
    <HeroSection />
    <AboutSection />
    <SkillsSection />
    <ProjectSection />
    <ContactSection />
    <AppFooter />
  </div>
</template>
