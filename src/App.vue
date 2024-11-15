<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>


<template>
  <div class="bg-black flex flex-col min-h-screen">
    <!-- Navigation bar -->
    <nav class="flex justify-center items-center px-4 py-4 mb-8">
      <h1 class="text-orange-200 font-bold text-xl mr-4">Kristofer</h1>
      <div class="flex space-x-6">
        <a href="#" @click.prevent="navigateTo('home')" class="text-orange-200 hover:text-gray-400">Home</a>
        <a href="#" @click.prevent="navigateTo('about')" class="text-orange-200 hover:text-gray-400">About</a>
        <!-- Add more links as needed -->
      </div>
      <button class="bg-orange-200 text-black px-4 py-2 rounded-md ml-4 hover:bg-gray-700">
        Let's Talk
      </button>
    </nav>

    <!-- Dynamic content rendering -->
    <component :is="currentPageComponent" />
  </div>
</template>

<script>
import Home from './Home.vue'; // Import Home component
import About from './About.vue'; // Import About component (currently empty)

export default {
  data() {
    return {
      currentPage: 'home', // Default page to display
    };
  },
  computed: {
    currentPageComponent() {
      return this.currentPage === 'home' ? Home : About; // Conditionally renders the page
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
/* Add any global styles here if necessary */
</style>






