<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
    <div class="bg-black flex flex-col min-h-screen">
      <div class="flex flex-col items-center justify-center flex-grow text-center bg-cover bg-center mb-16"
           style="background-image: url('/image/chips.png'); opacity: 0.85; height: 80vh;">
        <div class="z-10">
          <h2 class="text-orange-200 text-8xl font-bold">Web Designer</h2>
          <h3 class="text-orange-200 text-8xl mt-4 italic">& Developer</h3>
          <p class="text-orange-200 text-opacity-50 text-lg mt-6 max-w-xl">
            Providing web design, development, and SEO services to help your business stand out.
          </p>
        </div>
      </div>
  
      <div class="flex justify-center space-x-10 py-20">
        
        <div class="bg-gray-900 p-10 text-center">
          <h2 class="text-xl font-semibold mb-4 text-orange-200">WEB DESIGN</h2>
          <p class="text-gray-400 mb-6">
            Visually stunning web designs that captivate your audience by blending your brand voice and customer needs.
          </p>
          <a href="#" class="text-gray-400 flex items-center justify-center hover:text-white">
            <span>ABOUT WEBDESIGN</span>
            <svg class="ml-2 w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path>
            </svg>
          </a>
        </div>
  
        <div class="bg-gray-900 p-10 text-center">
          <h2 class="text-xl font-semibold mb-4 text-orange-200">DEVELOPMENT</h2>
          <p class="text-gray-400 mb-6">
            Get custom web development solutions that are tailored to your specifications, designed to deliver a flawless user experience.
          </p>
          <a href="#" class="text-gray-400 flex items-center justify-center hover:text-white">
            <span>ABOUT WEBFLOW</span>
            <svg class="ml-2 w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path>
            </svg>
          </a>
        </div>
  
        <div class="bg-gray-900 p-10 text-center">
          <h2 class="text-xl font-semibold mb-4 text-orange-200">CONTENT & SEO</h2>
          <p class="text-gray-400 mb-6">
            Proven SEO strategies that enhance your online performance, bringing you to the forefront of organic search results.
          </p>
          <a href="#" class="text-gray-400 flex items-center justify-center hover:text-white">
            <span>ABOUT SEO</span>
            <svg class="ml-2 w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path>
            </svg>
          </a>
        </div>
      </div>
  
      <section class="bg-black py-20 px-4">
        <div class="max-w-5xl mx-auto text-center">
          <h2 class="text-3xl font-light text-gray-300 mb-8">
            Selected <span class="italic font-semibold">Work</span>
          </h2>
          <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div class="relative group">
              <img src="/image/pc.png" alt="Space Project" class="w-full h-auto object-cover" />
              <div class="absolute inset-0 opacity-50 group-hover:opacity-75 transition duration-300"></div>
              <div class="absolute bottom-4 left-4 text-white"></div>
            </div>
            <div class="relative group">
              <img src="/image/phone.png" alt="Nova Project" class="w-full h-auto object-cover" />
              <div class="absolute inset-0 opacity-50 group-hover:opacity-75 transition duration-300"></div>
              <div class="absolute bottom-4 left-4 text-white"></div>
            </div>
            <div class="relative group">
              <img src="/image/phone2.png" alt="Sonic Project" class="w-full h-auto object-cover" />
              <div class="absolute inset-0 opacity-50 group-hover:opacity-75 transition duration-300"></div>
              <div class="absolute bottom-4 left-4 text-white"></div>
            </div>
            <div class="relative group">
              <img src="/image/pc2.png" alt="Solar Project" class="w-full h-auto object-cover" />
              <div class="absolute inset-0 opacity-50 group-hover:opacity-75 transition duration-300"></div>
              <div class="absolute bottom-4 left-4 text-white"></div>
            </div>
          </div>
          <a href="#" class="text-gray-400 mt-6 inline-block hover:text-white">
            <span>SEE ALL</span>
            <svg class="ml-1 w-4 h-4 inline" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path>
            </svg>
          </a>
        </div>
      </section>
  
      <section class="bg-black py-20 text-center">
        <div class="max-w-4xl mx-auto">
          <p class="text-gray-500 uppercase tracking-wide mb-2">The Process</p>
          <h2 class="text-6xl font-light text-orange-200 mb-4">Your Website</h2>
          <h3 class="text-5xl italic text-orange-200">in 5 steps</h3>
          <p class="text-gray-400 mt-4 max-w-2xl mx-auto">
            Our process ensures that we create a website tailored to your business needs.
          </p>
        </div>
  
        <div class="flex flex-col items-center py-20 space-y-10">
          <div class="max-w-md bg-gray-900 p-10 text-left text-gray-300">
            <h4 class="text-xl font-bold text-orange-200">01. Discovery Call</h4>
            <p>We get to know each other better, determine how I can assist you, and understand the goals you have for your website.</p>
          </div>
  
          <div class="max-w-md bg-gray-900 p-10 text-left text-gray-300">
            <h4 class="text-xl font-bold text-orange-200">02. Concept & Strategy</h4>
            <p>Together, we develop a strategy that combines your goals with the needs of your target audience. I create the first wireframes and an interactive prototype.</p>
            <ul class="list-disc list-inside mt-2 text-gray-400">
              <li>UX Design</li>
              <li>Wireframes</li>
              <li>Interactive Prototype</li>
            </ul>
          </div>
  
          <div class="max-w-md bg-gray-900 p-10 text-left text-gray-300">
            <h4 class="text-xl font-bold text-orange-200">03. Web Design</h4>
            <p>I create a high-end screen design tailored to your brand, ensuring it provides an excellent user experience.</p>
            <ul class="list-disc list-inside mt-2 text-gray-400">
              <li>Screen Design</li>
              <li>Mobile Responsive</li>
            </ul>
          </div>
  
          <div class="max-w-md bg-gray-900 p-10 text-left text-gray-300">
            <h4 class="text-xl font-bold text-orange-200">04. Web Development</h4>
            <p>The final design is brought to life through development, followed by tests and adjustments before launch.</p>
          </div>
  
          <div class="max-w-md bg-gray-900 p-10 text-left text-gray-300">
            <h4 class="text-xl font-bold text-orange-200">05. Launch & Optimization</h4>
            <p>The website goes live! I provide training and assistance to ensure smooth operation and am available for any questions.</p>
            <ul class="list-disc list-inside mt-2 text-gray-400">
              <li>Website Training</li>
              <li>Ongoing Support</li>
            </ul>
          </div>
        </div>
      </section>
  
      <header class="flex flex-col items-center justify-center flex-grow text-center p-8">
        <h1 class="text-7xl lg:text-8xl font-light text-beige-400 mb-4">
          <span class="float-left">Kristofer Mere</span>
        </h1>
  
        <div class="text-center mt-20">
          <p class="text-2xl lg:text-4xl italic font-light">A website that leaves <br><span class="font-bold">a lasting impression!</span></p>
        </div>
  
        <p class="text-gray-300 mt-8 text-lg max-w-2xl mx-auto">
          Hi, I'm Kristofer Mere - a freelancer specializing in premium web design, development, and SEO services. I'm passionate about creating unique and effective solutions for my clients, and I bring a personal touch to every project. Let's work together to bring your vision to life!
        </p>
  
        <div class="flex justify-center space-x-6 mt-10">
          <a href="#" class="text-beige-400 hover:text-white">
            <i class="fab fa-twitter fa-lg"></i>
          </a>
          <a href="#" class="text-beige-400 hover:text-white">
            <i class="fab fa-linkedin fa-lg"></i>
          </a>
          <a href="#" class="text-beige-400 hover:text-white">
            <i class="fab fa-instagram fa-lg"></i>
          </a>
          <a href="#" class="text-beige-400 hover:text-white">
            <i class="fab fa-behance fa-lg"></i>
          </a>
        </div>
      </header>
    </div>
    <section class="bg-black py-20 text-center">
    <p class="text-gray-500 uppercase tracking-wide mb-2">Project in mind?</p>
    <h2 class="text-5xl font-light text-beige-400 mb-4">Let’s make your <span class="italic font-semibold">Website shine</span></h2>
    <p class="text-gray-400 mt-4 max-w-md mx-auto">
        Premium web design, Webflow, and SEO services to help your business stand out.
    </p>
    <button class="bg-beige-400 text-black px-6 py-3 rounded-md mt-8 hover:bg-gray-700">
        Get in Touch
    </button>
</section>

  </template>
  
 
  
  <style scoped>

  .text-beige-400 {
    color: #d3b692; 
  }
  
  
  </style>
  