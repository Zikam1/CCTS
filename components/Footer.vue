<template>
  <footer class="bg-gray-900 text-gray-300 py-10">
    <div class="container mx-auto grid grid-cols-1 md:grid-cols-4 gap-8">
      
      <!-- About Section -->
      <div>
        <h3 class="text-lg font-bold text-white">TechDesign</h3>
        <p class="mt-4">
          We create cutting-edge tech designs for innovative businesses. Our expertise in technology and design sets us apart.
        </p>
      </div>
      
      <!-- Quick Links Section -->
      <div>
        <h3 class="text-lg font-bold text-white">Quick Links</h3>
        <ul class="mt-4 space-y-2">
          <li><a href="/" class="hover:text-blue-500">Home</a></li>
          <li><a href="/projects" class="hover:text-blue-500">Projects</a></li>
          <li><a href="/about" class="hover:text-blue-500">About Us</a></li>
          <li><a href="/contact" class="hover:text-blue-500">Contact</a></li>
        </ul>
      </div>
      
      <!-- Social Links Section -->
      <div>
        <h3 class="text-lg font-bold text-white">Follow Us</h3>
        <ul class="mt-4 flex space-x-4">
          <li><a href="#" class="hover:text-blue-500"><svg class="w-6 h-6" fill="currentColor" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 0a12 12 0 1012 12A12 12 0 0012 0zm5.25 8h-1.78a.95.95 0 00-.95.95v1.58h2.57l-.41 2.58h-2.16v6.43h-2.67V13.11h-1.82v-2.58h1.82V9.33a3.16 3.16 0 013.16-3.16h1.76v2.83z"/></svg></a></li>
          <li><a href="#" class="hover:text-blue-500"><svg class="w-6 h-6" fill="currentColor" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M22.54 6.42a8.87 8.87 0 01-2.54.7A4.45 4.45 0 0021.95 4a8.91 8.91 0 01-2.82 1.08 4.43 4.43 0 00-7.54 4.04A12.57 12.57 0 012.09 5.1a4.42 4.42 0 001.37 5.91A4.41 4.41 0 012 10.67v.05a4.43 4.43 0 003.55 4.34 4.43 4.43 0 01-2 .08A4.44 4.44 0 007.8 17a8.9 8.9 0 01-5.51 1.91A8.92 8.92 0 002 19.9a12.56 12.56 0 006.79 1.99c8.13 0 12.57-6.73 12.57-12.57v-.57a9.12 9.12 0 002.24-2.33"/></svg></a></li>
          <li><a href="#" class="hover:text-blue-500"><svg class="w-6 h-6" fill="currentColor" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M24 4.56v15.02A4.42 4.42 0 0119.57 24H4.43A4.42 4.42 0 010 19.58V4.43A4.42 4.42 0 014.43 0h15.15A4.42 4.42 0 0124 4.56zM8.19 12a3.81 3.81 0 10-3.81 3.81 3.81 3.81 0 003.81-3.81zm0 5.86a5.86 5.86 0 11-5.86-5.86 5.86 5.86 0 015.86 5.86zm10.5-10.5a2.19 2.19 0 11-2.18 2.19 2.19 2.19 0 012.18-2.19zm0 1.31a.88.88 0 10.88.88.87.87 0 00-.88-.88zm0 10.05c-3.14 0-5.68-2.54-5.68-5.68s2.54-5.68 5.68-5.68 5.68 2.54 5.68 5.68-2.54 5.68-5.68 5.68zm0-10.5a4.82 4.82 0 00-4.82 4.82 4.82 4.82 0 004.82 4.82 4.82 4.82 0 004.82-4.82 4.82 4.82 0 00-4.82-4.82z"/></svg></a></li>
        </ul>
      </div>
      
      <!-- Newsletter Section -->
      <div>
        <h3 class="text-lg font-bold text-white">Subscribe to our Newsletter</h3>
        <form @submit.prevent="subscribe" class="mt-4 flex flex-col space-y-2">
          <input type="email" placeholder="Your email address" class="p-2 bg-gray-800 text-gray-300 rounded-md focus:ring-2 focus:ring-blue-500 focus:outline-none">
          <button class="bg-blue-500 text-white px-4 py-2 rounded-md hover:bg-blue-600">Subscribe</button>
        </form>
      </div>
    </div>
    
    <!-- Copyright -->
    <div class="mt-8 text-center text-gray-400">
      <p>&copy; 2024 Clarionconcept. All rights reserved.</p>
    </div>
  </footer>
</template>

<script setup>
function subscribe() {
  alert("Subscribed successfully!");
}
</script>
