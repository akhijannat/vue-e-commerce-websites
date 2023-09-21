<script setup>
import { RouterView } from "vue-router";
import HeaderSection from "./components/HeaderSection.vue";
import Hero from "./components/Hero.vue";
import Footer from "./components/FooterSection.vue";
</script>

<template>
  <HeaderSection />
  <Hero />

  <RouterView />

  <Footer />
</template>

<style scoped></style>
