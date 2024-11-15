<template>
  <div class="about-page bg-black min-h-screen text-beige-400 flex flex-col items-center p-8">
    
    <div class="text-center mt-10">
      <h1 class="text-7xl font-light">Kristofer Mere</h1>
      <p class="text-lg mt-4 text-gray-500 uppercase tracking-widest">Your Partner in Bringing Your Web Design Vision to Life</p>
    </div>

 
    <div class="max-w-2xl text-center mt-10">
      <p class="text-gray-300 leading-relaxed">
        As a freelance web designer and developer, I bring a unique combination of creativity and technical expertise to every project. 
        With a keen eye for design and a passion for delivering user-friendly web experiences, I work closely with clients to understand 
        their needs and bring their vision to life.
      </p>
      <p class="text-gray-300 leading-relaxed mt-4">
        My approach is rooted in collaboration and communication, and I take pride in my ability to explain technical concepts in simple terms. 
        Whether I'm developing a new website from scratch or optimizing an existing site for search engines, I always strive for excellence in both form 
        and function. With a dedication to quality and a commitment to staying on top of the latest trends and technologies, I am confident in my ability 
        to deliver exceptional results that exceed my clients' expectations.
      </p>
    </div>

    
    <div class="mt-10 mb-10">
      
    </div>

    <div class="flex space-x-4">
      <a href="#" class="social-btn"><i class="fab fa-instagram"></i> Instagram</a>
      <a href="#" class="social-btn"><i class="fab fa-twitter"></i> Twitter</a>
      <a href="#" class="social-btn"><i class="fab fa-facebook"></i> Facebook</a>
      <a href="#" class="social-btn"><i class="fab fa-behance"></i> Behance</a>
      <a href="#" class="social-btn"><i class="fab fa-dribbble"></i> Dribbble</a>
      <a href="#" class="social-btn"><i class="fab fa-pinterest"></i> Pinterest</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'About',
};
</script>

<style scoped>
.about-page {
  color: #d3b692;
}

.social-btn {
  display: flex;
  align-items: center;
  padding: 0.5rem 1rem;
  border: 1px solid #d3b692;
  color: #d3b692;
  text-transform: uppercase;
  font-size: 0.875rem;
  transition: color 0.3s, background-color 0.3s;
}

.social-btn:hover {
  color: black;
  background-color: #d3b692;
}

.text-beige-400 {
  color: #d3b692;
}

.text-gray-500 {
  color: #6b7280;
}
</style>


