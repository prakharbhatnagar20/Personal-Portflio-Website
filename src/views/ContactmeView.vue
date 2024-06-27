<template>
  <body class="bg-gray-100 font-sans">
    <!-- Contact Section -->
    <section class="container mx-auto my-8 p-8 bg-white shadow-md rounded-md">
      <h2 class="text-3xl font-bold mb-6">Contact Me</h2>

      <!-- Contact Form -->
      <form @submit.prevent="handleSubmit">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
          <div class="mb-4">
            <label for="name" class="block text-gray-700 text-sm font-bold mb-2">Your Name</label>
            <input type="text" id="name" name="name" v-model="form.name" class="w-full px-4 py-2 border rounded-md focus:outline-none focus:border-blue-500">
          </div>

          <div class="mb-4">
            <label for="email" class="block text-gray-700 text-sm font-bold mb-2">Your Email</label>
            <input type="email" id="email" name="email" v-model="form.email" class="w-full px-4 py-2 border rounded-md focus:outline-none focus:border-blue-500">
          </div>
        </div>

        <div class="mb-4">
          <label for="message" class="block text-gray-700 text-sm font-bold mb-2">Your Message</label>
          <textarea id="message" name="message" v-model="form.message" rows="4" class="w-full px-4 py-2 border rounded-md focus:outline-none focus:border-blue-500"></textarea>
        </div>

        <button type="submit" class="bg-blue-500 text-white px-6 py-3 rounded-md hover:bg-blue-600 focus:outline-none">Send Message</button>
      </form>
    </section>

    <!-- Toast Notification -->
    <transition name="fade" v-if="showToast">
      <div class="fixed top-4 right-4 bg-green-500 text-white py-2 px-4 rounded-md shadow-md">
        Message sent successfully!
      </div>
    </transition>
  </body>
</template>

<script setup>
import { ref } from 'vue'

const form = ref({
  name: '',
  email: '',
  message: ''
})

const showToast = ref(false)

const handleSubmit = () => {
  // Simulate form submission
  setTimeout(() => {
    // Show toast notification
    showToast.value = true

    // Hide toast after 3 seconds
    setTimeout(() => {
      showToast.value = false
    }, 3000)
  }, 500)
}
</script>

<style scoped>
.fade-enter-active, .fade-leave-active {
  transition: opacity 0.5s;
}
.fade-enter-from, .fade-leave-to {
  opacity: 0;
}
</style>
