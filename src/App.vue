<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="bg-black flex flex-col min-h-screen">
    <!-- Navigation Bar -->
    <nav class="flex justify-center items-center px-4 py-4 mb-8">
      <h1 class="text-orange-200 font-bold text-xl mr-4">arik.</h1>

      <div class="flex space-x-6">
        <a href="#" class="text-orange-200 hover:text-gray-400">Services</a>
        <a href="#" class="text-orange-200 hover:text-gray-400">Work</a>
        <a href="#" class="text-orange-200 hover:text-gray-400">About</a>
        <a href="#" class="text-orange-200 hover:text-gray-400">Blog</a>
        <a href="#" class="text-orange-200 hover:text-gray-400">Pages</a>
      </div>

      <button class="bg-orange-200 text-black px-4 py-2 rounded-md ml-4 hover:bg-gray-700">
        Let's Talk
      </button>
    </nav>

    <!-- Hero Section -->
    <div class="flex flex-col items-center justify-center flex-grow text-center bg-cover bg-center mb-16"
         style="background-image: url('/image/chips.png'); opacity: 0.85; height: 80vh;">
      <div class="z-10">
        <h2 class="text-orange-200 text-8xl font-bold">Web Designer</h2>
        <h3 class="text-orange-200 text-8xl mt-4 italic">& Developer</h3>
        <p class="text-orange-200 text-opacity-10 text-lg mt-6 max-w-xl">
          Providing web design, development, and SEO services to help your business stand out.
        </p>
      </div>
    </div>

    <!-- Services Section -->
    <div class="flex justify-center space-x-10 py-20">
      <!-- Web Design -->
      <div class="bg-gray-900 p-10 text-center">
        <h2 class="text-xl font-semibold mb-4 text-orange-200">WEB DESIGN</h2>
        <p class="text-gray-400 mb-6">
          Visually stunning web designs that captivate your audience by blending your brand voice and customer needs.
        </p>
        <a href="#" class="text-gray-400 flex items-center justify-center hover:text-white">
          <span>ABOUT WEBDESIGN</span>
          <svg class="ml-2 w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path>
          </svg>
        </a>
      </div>

      <!-- Development -->
      <div class="bg-gray-900 p-10 text-center">
        <h2 class="text-xl font-semibold mb-4 text-orange-200">DEVELOPMENT</h2>
        <p class="text-gray-400 mb-6">
          Get custom web development solutions that are tailored to your specifications, designed to deliver a flawless user experience.
        </p>
        <a href="#" class="text-gray-400 flex items-center justify-center hover:text-white">
          <span>ABOUT WEBFLOW</span>
          <svg class="ml-2 w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path>
          </svg>
        </a>
      </div>

      <!-- Content & SEO -->
      <div class="bg-gray-900 p-10 text-center">
        <h2 class="text-xl font-semibold mb-4 text-orange-200">CONTENT & SEO</h2>
        <p class="text-gray-400 mb-6">
          Proven SEO strategies that enhance your online performance, bringing you to the forefront of organic search results.
        </p>
        <a href="#" class="text-gray-400 flex items-center justify-center hover:text-white">
          <span>ABOUT SEO</span>
          <svg class="ml-2 w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path>
          </svg>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
};
</script>

<style scoped>
/* Add any additional styles here */
</style>


