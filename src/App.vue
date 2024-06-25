<script setup>
import { ref } from 'vue'
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'

const isMenuOpen = ref(false)
</script>

<template>
  <header>
    <div class="shadow bg-white">
      <div class="h-16 mx-auto px-5 flex items-center justify-between">
        <a class="text-2xl hover:text-cyan-500 transition-colors cursor-pointer">Prakhar</a>

        <!-- Hamburger icon for mobile -->
        <div class="md:hidden cursor-pointer" @click="isMenuOpen = !isMenuOpen">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
          </svg>
        </div>

        <!-- Menu items -->
        <ul :class="{'hidden': !isMenuOpen, 'flex': isMenuOpen}" class="flex-col md:flex-row md:flex items-center justify-between gap-3 md:gap-10 md:static absolute top-16 left-0 right-0 bg-white md:bg-transparent p-5 md:p-0 z-50">
          <li>
            <RouterLink to="/" class="hover:text-cyan-500 transition-colors">Home</RouterLink>
          </li>
          <li>
            <RouterLink to="/about" class="hover:text-cyan-500 transition-colors">About</RouterLink>
          </li>
          <li>
            <RouterLink to="/projects" class="hover:text-cyan-500 transition-colors">Projects</RouterLink>
          </li>
          <li>
            <RouterLink to="/contact" class="hover:text-cyan-500 transition-colors">Contact Me</RouterLink>
          </li>
        </ul>
      </div>
    </div>
  </header>

  <div class="z-5">
    <RouterView />
  </div>
  <!-- <footer class="bg-gray-800 text-white text-center fixed bottom-1 w-screen py-4">
    <p>&copy; 2024 Prakhar Bhatnagar. All rights reserved.</p>
  </footer> -->
</template>

<style scoped>
/* Add your custom styles here if needed */
</style>

