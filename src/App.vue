1<template>
<div id="app" class="min-h-screen flex flex-col">
    <!-- Navigation -->
    <header class="bg-[#2D7B88] text-white p-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold">Dalton Teasley</h1>
      <nav>
        <a href="#" class="mx-2 hover:underline">About</a>
        <a href="#" class="mx-2 hover:underline">Portfolio</a>
        <a href="#" class="mx-2 hover:underline">Contact</a>
      </nav>
    </header>

    <!-- Hero Section -->
    <section class="flex flex-col md:flex-row items-center justify-center flex-grow bg-[#CAD4D3] p-8 text-center md:text-left">
      <img src="@/assets/profile.jpeg" alt="Dalton Teasley" class="rounded-full shadow-lg mb-4 md:mb-0 md:mr-8">
      <div>
        <h2 class="text-3xl font-semibold mb-2">Hi, I’m Dalton!</h2>
        <p class="text-lg max-w-md">
          Put some awe-inspiring text here please.
        </p>
      </div>
    </section>

    <!-- Footer -->
    <footer class="bg-[#2D7B88] text-white text-center p-4">
      <p>&copy; 2025 Dalton Teasley | 
        <a href="https://github.com/d-teasley" class="underline">GitHub</a> • 
        <a href="https://linkedin.com/in/dalton-teasley-dt017" class="underline">LinkedIn</a>
      </p>
    </footer>
  </div>
</template>

<script>
/* NOT NEEDED import HelloWorld from './components/HelloWorld.vue' */

export default {
  name: 'App'
}
</script>

<style>
#app {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  padding: 0;
  background-color: #345060; /* REPLACE */
  font-family: 'Arial', sans-serif;
  text-align: center;
}

#app img {
  max-width: 100%;
  height: auto;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  margin-bottom: 20px;
  object-fit: cover;
}

#app h1, p {
  margin: 10px 0;
}
  
  /* OLD #APP STYLING font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px; */

body {
  margin: 0;
  padding: 0;
  background-color: #345060;
}
</style>
