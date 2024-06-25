<template>
  <div class="text-6xl text-center m-5 font-bold">About Me</div>
  <div class="grid grid-cols-1 md:grid-cols-2 gap-4 m-4">

    <!-- Education Section -->
    <div class="bg-blue-200 text-center border text-2xl rounded-xl shadow-lg p-6 font-mono">
      <h1 class="font-bold text-4xl mb-4">Education</h1>
      <div class="grid grid-cols-2 gap-4 text-left">
        <div>
          <h2 class="font-semibold">High School</h2>
          <p>Ryan International School</p>
          <p class="font-semibold">92.6%</p>
        </div>
        <div>
          <h2 class="font-semibold">Intermediate</h2>
          <p>Ryan International School</p>
          <p class="font-semibold">87%</p>
        </div>
        <div>
          <h2 class="font-semibold">Graduation</h2>
          <p>G.L. Bajaj Institute of Technology and Management</p>
          <p class="font-semibold">7 CGPA (average)</p>
        </div>
      </div>
    </div>

    <!-- Skills Section -->
    <div class="bg-blue-200 text-center border text-2xl rounded-xl shadow-lg p-6 font-mono">
      <div class="flex flex-col items-center">
        <div class="font-bold text-4xl w-full mb-4">
          Skills
        </div>
        
        <!-- Languages -->
        <div class="font-bold text-2xl text-left w-full mb-2">
          Languages:
        </div>
        <div class="text-xl grid grid-cols-2 gap-2 w-full text-left">
          <div class="font-mono">Java</div>
          <div class="font-mono">Kotlin</div>
          <div class="font-mono">JavaScript</div>
          <div class="font-mono">CSS</div>
          <div class="font-mono">HTML</div>
        </div>
        
        <!-- Frameworks -->
        <div class="font-bold text-2xl text-left w-full mt-6 mb-2">
          Frameworks:
        </div>
        <div class="text-xl grid grid-cols-2 gap-2 w-full text-left">
          <div class="font-mono">Springboot</div>
          <div class="font-mono">Vue.js</div>
          <div class="font-mono">Jetpack Compose</div>
          <div class="font-mono">Tailwind CSS</div>
        </div>
        
        <!-- Tools -->
        <div class="font-bold text-2xl text-left w-full mt-6 mb-2">
          Tools:
        </div>
        <div class="text-xl grid grid-cols-2 gap-2 w-full text-left">
          <div class="font-mono">Android Studio</div>
          <div class="font-mono">VS Code</div>
          <div class="font-mono">Material Design</div>
          <div class="font-mono">Figma</div>
        </div>
      </div>
    </div>

  </div>
</template>


<style scoped>
/* Add any additional custom styles here if needed */
</style>

