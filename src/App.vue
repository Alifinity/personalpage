<script setup lang="ts">
import About from "./components/About.vue";
import Skills from "./components/Skills.vue";
import Contact from "./components/Contact.vue";
</script>

<template>
  <div id="app" class="min-h-screen bg-slate-900 text-slate-300">
    <main class="mx-auto w-full max-w-4xl px-4 py-16">
      <div class="space-y-0">
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
