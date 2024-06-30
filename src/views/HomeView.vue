
<template>
  <body class="bg-gray-100 font-sans">
  
    <!-- Hero Section with Profile Photo -->
    <section class="bg-blue-800 text-white min-h-screen flex flex-col justify-center items-center">
        <img src="/photo.png" alt="Your Name" class="h-80 w-80 object-cover mt-4 mb-2">
        <h1 class="text-4xl lg:text-5xl font-bold mb-4 mt-8 text-center typing">Welcome to My Portfolio</h1>
        <p class="pl-4 pr-4 pt-2 pb-4 text-center max-w-2xl mx-auto font-mono text-lg">
            I'm Prakhar Bhatnagar, a budding Android developer with a passion for creating mobile magic. I'm diving headfirst into the world of Android apps, learning the ropes, and coding my way to awesome.
    
            My journey is just beginning, and I'm on a mission to turn ideas into functional apps that make life easier and more fun. Java and Kotlin are my trusty sidekicks, and Android Studio is where the magic happens.
    
            Join me as I explore the endless possibilities of mobile development, one line of code at a time. Let's connect, share knowledge, and build something incredible together!
        </p>
        <div class="flex mt-4 mb-4">
          <a href="https://www.linkedin.com/in/prakhar-bhatnagar-9ba25722a/" target="_blank" class="mr-4">
            <img src="/linked.png" alt="LinkedIn" class="h-8 w-8">
          </a>
          <a href="https://github.com/prakharbhatnagar20" target="_blank" class="mr-4">
            <img src="/github.png" alt="GitHub" class="h-8 w-8">
          </a>
          <a href="https://www.instagram.com/prakhar__20" target="_blank"class="mr-4">
            <img src="/insta.png" alt="Instagram" class="h-8 w-8">
          </a>
          <a href="https://leetcode.com/u/prakhar__20/" target="_blank"class="mr-4">
            <img src="/leetcode.png" alt="Instagram" class="h-8 w-8">
          </a>
        </div>
    </section>
  
    <!-- Footer -->
    <footer class="bg-gray-800 text-white text-center w-screen py-4">
        <p>&copy; 2024 Prakhar Bhatnagar. All rights reserved.</p>
    </footer>
  
  </body>
</template>

<style scoped>
@keyframes typing {
  from { width: 0; }
  to { width: 40%; }
}

@keyframes blink-caret {
  from, to { border-color: transparent; }
  50% { border-color: white; }
}

.typing {
  white-space: nowrap;
  overflow: hidden;
  border-right: .15em solid white;
  padding-bottom: 0.1em; /* Add padding to prevent cutting off */
  line-height: 1.2; /* Adjust line height to create more space */
  animation:
    typing 4s steps(40, end),
    blink-caret .75s step-end infinite;
}

/* @keyframes gradient {
  0% { background-position: 0% 50%; }
  5% { background-position: 5% 50%; }
  10% { background-position: 10% 50%; }
  15% { background-position: 15% 50%; }
  20% { background-position: 20% 50%; }
  25% { background-position: 25% 50%; }
  30% { background-position: 30% 50%; }
  35% { background-position: 35% 50%; }
  40% { background-position: 40% 50%; }
  45% { background-position: 45% 50%; }
  50% { background-position: 50% 50%; }
  55% { background-position: 55% 50%; }
  60% { background-position: 60% 50%; }
  65% { background-position: 65% 50%; }
  70% { background-position: 70% 50%; }
  75% { background-position: 75% 50%; }
  80% { background-position: 80% 50%; }
  85% { background-position: 85% 50%; }
  90% { background-position: 90% 50%; }
  95% { background-position: 95% 50%; }
  100% { background-position: 100% 50%; }
} */

/* .dynamic-bg {
  background: linear-gradient(270deg, #1e3a8a, #2d59a1, #3b82f6, #2563eb, #b90cf2,#c91b3e, #c91b3e, #faa12c,#7e8822,#41c91b,#20f1c0,#1b52c9);
  background-size: 800% 800%;
  animation: gradient 30s ease infinite;
} */

@media (max-width: 1024px) {
  .typing {
    font-size: 3xl;
  }
}

@media (max-width: 768px) {
  .typing {
    font-size: 2xl;
  }

  .dynamic-bg {
    background-size: 1200% 1200%;
  }
}

@media (max-width: 480px) {
  .typing {
    font-size: xl;
  }

  .dynamic-bg {
    background-size: 1600% 1600%;
  }
}
</style>

  
  

