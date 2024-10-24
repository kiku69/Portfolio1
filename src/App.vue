<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="bg-black min-h-screen flex flex-col ">
    <nav class="flex justify-center items-center px-4 py-2">
      <h1 class="text-orange-200 font-bold text-xl mr-4">arik.</h1>
 
      <div class="flex space-x-6">
        <a href="#" class="text-orange-200 hover:text-gray-400">Services</a>
        <a href="#" class="text-orange-200 hover:text-gray-400">Work</a>
        <a href="#" class="text-orange-200 hover:text-gray-400">About</a>
        <a href="#" class="text-orange-200 hover:text-gray-400">Blog</a>
        <a href="#" class="text-orange-200 hover:text-gray-400">Pages</a>
      </div>
 
      <button class="bg-orange-200 text-black px-4 py-2 rounded-md  ml-4 hover:bg-gray-700">
        Let's Talk
      </button>
    </nav>
 
    <div class="flex flex-col items-center justify-center flex-grow text-center bg-cover bg-center"
         style="background-image: url('/image/chips.png'); opacity: 0.85;">
      <div class="z-10">
        <h2 class="text-orange-200 text-9xl font-bold">Web Designer</h2>
        <h3 class="text-orange-200 text-9xl mt-4 italic">& Developer</h3>
        <p class="text-orange-200 text-opacity-10 text-lg mt-6 max-w-xl ">
          Providing web design, development, and SEO services to help your business stand out.
        </p>
      </div>
    </div>
  </div>
</template>
kontekstimenüü on olemas
