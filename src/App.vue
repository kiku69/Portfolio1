<script setup>
import Navbar from './components/Navbar.vue'
</script>


<template>
 <Navbar></Navbar>
 
</template>

<script>
import Home from './Home.vue'; 
import About from './About.vue'; 

export default {
  data() {
    return {
      currentPage: 'home',
    };
  },
  computed: {
    currentPageComponent() {
      return this.currentPage === 'home' ? Home : About; 
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






