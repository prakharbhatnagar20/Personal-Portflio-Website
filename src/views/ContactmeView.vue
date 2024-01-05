<template>
    <body class="bg-gray-100 font-sans">

<!-- Contact Section -->
<section class="container mx-auto my-8 p-8 bg-white shadow-md rounded-md">
  <h2 class="text-3xl font-bold mb-6">Contact Me</h2>
  
  <!-- Contact Form -->
  <form action="#" method="post">
    <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
      <div class="mb-4">
        <label for="name" class="block text-gray-700 text-sm font-bold mb-2">Your Name</label>
        <input type="text" id="name" name="name" class="w-full px-4 py-2 border rounded-md focus:outline-none focus:border-blue-500">
      </div>

      <div class="mb-4">
        <label for="email" class="block text-gray-700 text-sm font-bold mb-2">Your Email</label>
        <input type="email" id="email" name="email" class="w-full px-4 py-2 border rounded-md focus:outline-none focus:border-blue-500">
      </div>
    </div>

    <div class="mb-4">
      <label for="message" class="block text-gray-700 text-sm font-bold mb-2">Your Message</label>
      <textarea id="message" name="message" rows="4" class="w-full px-4 py-2 border rounded-md focus:outline-none focus:border-blue-500"></textarea>
    </div>

    <button type="submit" class="bg-blue-500 text-white px-6 py-3 rounded-md hover:bg-blue-600 focus:outline-none">Send Message</button>
  </form>
</section>



</body>
</template>