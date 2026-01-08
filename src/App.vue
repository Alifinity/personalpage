<script setup lang="ts">
import About from "./components/About.vue";
import Skills from "./components/Skills.vue";
import Contact from "./components/Contact.vue";
</script>

<template>
  <div id="app" class="min-h-screen content-center bg-slate-900 text-slate-300 flex items-center justify-center">
    <main class="w-full max-w-4xl px-4">
      <div class="space-y-4">
        <About />
        <Skills />
        <Contact />
      </div>
    </main>
  </div>
</template>

<style>
html {
  scroll-behavior: smooth;
}
</style>
