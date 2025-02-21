<template>
    <div class="contact-page bg-black min-h-screen flex flex-col items-center p-8">
      <div class="text-center mt-10">
        <h1 class="text-4xl font-light text-beige-400">Let's get in touch.</h1>
      </div>
      <form class="mt-10 max-w-lg w-full" @submit.prevent="submitForm">
        <div class="mb-6">
          <label for="name" class="block text-beige-500 text-sm uppercase tracking-wider mb-2">Name</label>
          <input
            id="name"
            type="text"
            class="w-full px-4 py-3 bg-black text-beige-400 border border-beige-500 rounded-sm focus:outline-none focus:ring focus:ring-beige-500"
            required
          />
        </div>
        <div class="mb-6">
          <label for="email" class="block text-beige-500 text-sm uppercase tracking-wider mb-2">Email</label>
          <input
            id="email"
            type="email"
            class="w-full px-4 py-3 bg-black text-beige-400 border border-beige-500 rounded-sm focus:outline-none focus:ring focus:ring-beige-500"
            required
          />
        </div>
        <div class="mb-6">
          <label for="message" class="block text-beige-500 text-sm uppercase tracking-wider mb-2">Message</label>
          <textarea
            id="message"
            rows="5"
            class="w-full px-4 py-3 bg-black text-beige-400 border border-beige-500 rounded-sm focus:outline-none focus:ring focus:ring-beige-500"
            required
          ></textarea>
        </div>
        <button class="bg-orange-200 text-black px-6 py-3 rounded-md w-full animate-bounce animate-infinite">
  SEND MESSAGE
</button>

          
      </form>
    </div>
  </template>
  
  <script>
  export default {
    name: "Contact",
    methods: {
      submitForm() {
        alert("Thank you for your message!");
      },
    },
  };
  </script>
  
  <style scoped>
  .contact-page {
    color: #d3b692;
  }
  </style>
  