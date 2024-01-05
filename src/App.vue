<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <!-- component -->
<div class="shadow bg-white">
  <div class="h-16 mx-auto px-5 flex items-center justify-between">
      <a class="text-2xl hover:text-cyan-500 transition-colors cursor-pointer">Prakhar</a>
      
      <ul class="flex items-center justify-between gap-3 md:gap-10">
        <li><RouterLink to="/" class="hover:text-cyan-500 transition-colors">Home</RouterLink></li>
        <li><RouterLink to="/about" class="hover:text-cyan-500 transition-colors">About</RouterLink></li>
        <li><RouterLink to="/projects" class="hover:text-cyan-500 transition-colors">Projects</RouterLink></li>
        <li><RouterLink to="/contact" class="hover:text-cyan-500 transition-colors" >Contact Me</RouterLink></li>
      </ul>
  </div>
</div>
  </header>

  <RouterView />
  <footer class="bg-gray-800 text-white text-center py-4 object-bottom">
    <p>&copy; 2024 Prakhar Bhatnagar. All rights reserved.</p>
  </footer>
</template>

<style scoped>

</style>
