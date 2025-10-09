<template>
<div id="app" 
class="min-h-screen flex flex-col bg-[#1E1E1E] text-gray-100">
   
<!-- Navigation -->
    <header class="bg-[#AB67A1] text-white px-6 py-4 flex justify-between items-center w-full fixed top-0 left-0 z-50 shadow-md">
      <h1 class="text-2xl font-bold tracking-wide">Dalton Teasley</h1>
      <nav class="space-x-4">
        <a href="#" class="hover:text-gray-200 transition">About</a>
        <a href="#" class="hover:text-gray-200 transition">Portfolio</a>
        <a href="#" class="hover:text-gray-200 transition">Contact</a>
      </nav>
    </header>

    <!-- Hero Section -->
    <section class="flex flex-col md:flex-row justify-center items-center flex-grow bg-[#2E3138] py-16 px-8 mt-24 mx-4 rounded-lg shadow-2x1 text-center md:text-left transition-transform duration-300 hover:scale-[1.01]">
      
      <img
        src="@/assets/profile.jpeg"
        alt="Dalton Teasley"
        class="h-64 w-64 object-cover rounded-full shadow-lg mb-6 md:mb-0 md:mr-8">
      <div>
        <h2 class="text-4xl font-semibold mb-3 text-white">Hi, I’m Dalton!</h2>
        <p class="text-lg max-w-md text-gray-300 leading-relaxed">
          I'm into music, tech, and creating things that look and sound cool. 
          I like trying new things like making beats, messing with code, or making videos.
          Always learning, always curious, and usually caffeinated.
        </p>
      </div>
    </section>

    <!-- Footer -->
    <footer class="bg-[#AB67A1] text-white text-center p-4 mt-20 w-full">
      <p class="text-sm md:text-base">&copy; 2025 Dalton Teasley | 
        <a href="https://github.com/d-teasley" class="underline hover:text-gray-200 transition">GitHub</a> • 
        <a href="https://linkedin.com/in/dalton-teasley-dt017" class="underline hover:text-gray-200 transition">LinkedIn</a>
      </p>
    </footer>
  </div>
</template>

<script>

export default {
  name: 'App'
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&display=swap');

#app {
  font-family: 'Poppins', 'Inter', sans-serif;
}
</style>