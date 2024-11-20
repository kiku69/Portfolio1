<script setup>
</script>

<template>
  <div class="bg-black flex flex-col min-h-screen">
    <nav class="flex justify-center items-center px-4 py-4 mb-8">
      <h1 class="text-orange-200 font-bold text-xl mr-4">Kristofer</h1>

      <div class="flex space-x-6">
        <a
          href="#"
          @click.prevent="navigateTo('home')"
          class="text-orange-200 hover:text-gray-400"
        >
          Home
        </a>
        <a
          href="#"
          @click.prevent="navigateTo('about')"
          class="text-orange-200 hover:text-gray-400"
        >
          About
        </a>
      </div>

      <button
        @click.prevent="navigateTo('contact')"
        class="bg-orange-200 text-black px-4 py-2 rounded-md ml-4 hover:bg-gray-700"
      >
        Let's Talk
      </button>
    </nav>

    <component :is="currentPageComponent" />
  </div>
</template>

<script>
import Home from '/src/Home.vue';
import About from '/src/About.vue';
import Contact from '/src/Contact.vue'; 

export default {
  data() {
    return {
      currentPage: 'home', 
    };
  },
  computed: {
    currentPageComponent() {
      if (this.currentPage === 'home') return Home;
      if (this.currentPage === 'about') return About;
      return Contact; 
    },
  },
  methods: {
    navigateTo(page) {
      
      this.currentPage = page;
    },
  },
};
</script>

<style scoped>

</style>
