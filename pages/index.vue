<template>
    <section>
  <!-- Hero Section -->
  <section class="flex flex-col md:flex-row items-center py-16 px-4 md:px-16 lg:px-32 bg-gray-900">
    <div class="md:w-1/2 space-y-4 mx-auto lp:pl-8 max-w-lg">
      <h1 class="text-3xl md:text-5xl text-white font-bold md:mb-4  lg:mb-8 lg:mt-0">Efficiency through Innovation</h1>
      <p class="text-white">Discover cutting-edge technology to drive your business forward.</p>
      <div class="flex space-x-4">
        <button class="bg-blue-500 text-white px-6 py-3 rounded-md hover:bg-blue-600">Explore Features</button>
        <button class="bg-gray-300 text-blue-600 px-6 py-3 rounded-md hover:bg-gray-400">Contact Sales</button>
      </div>
    </div>
    <div class="md:w-1/2 hidden md:block">
      <!-- <img src="/assets/zik.jpg" alt="Tech illustration" class="w-full h-auto"> -->
    </div>
  </section>
     
   
     <!-- Services Section -->
<div class="py-16 bg-gray-100">
  <div class="container mx-auto text-center px-4 lg:px-32">
    <h2 class="text-3xl font-bold mb-8">Our Services</h2>
    <!-- Two columns for laptops, single column for smaller screens -->
    <div class="grid grid-cols-1 md:grid-cols-2 gap-8 px-4 lg:px-0">
      <!-- Service Card 1 -->
      <div class="p-6 bg-white rounded-md shadow-md hover:shadow-lg">
        <div class="text-blue-500 mb-4">
          <svg class="w-12 h-12 mx-auto" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c.24-1.734 1.525-3 3-3 1.657 0 3 1.343 3 3 0 1.657-1.343 3-3 3-1.657 0-3 1.343-3 3 0 1.475 1.266 2.76 3 3m-3 0h-4a4 4 0 01-4-4v-4a4 4 0 014-4h4m0 0h-4" />
          </svg>
        </div>
        <h3 class="text-xl font-semibold">Cloud Solutions</h3>
        <p class="mt-4 text-gray-600">We provide infrastructure management cybersecurity, and IT support to ensure system reliability and operational efficiency.</p>
      </div>

      <!-- Service Card 2 -->
      <div class="p-6 bg-white rounded-md shadow-md hover:shadow-lg">
        <div class="text-blue-500 mb-4">
          <svg class="w-12 h-12 mx-auto" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16.88 3.549l2.122 2.122A12 12 0 0115.474 12H12m-1 0H5.12l2.12-2.122M21 21L3 3" />
          </svg>
        </div>
        <h3 class="text-xl font-semibold">Digital Technology</h3>
        <p class="mt-4 text-gray-600">We provide reliable digital solutions that support data analytics, automation, and ultimately improve decision-making and optimize processes across industries.</p>
      </div>

      <!-- Service Card 3 -->
      <div class="p-6 bg-white rounded-md shadow-md hover:shadow-lg">
        <div class="text-blue-500 mb-4">
          <svg class="w-12 h-12 mx-auto" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8V12l3 3M4 6h16M4 12h16M4 18h16" />
          </svg>
        </div>
        <h3 class="text-xl font-semibold">IT Services</h3>
        <p class="mt-4 text-gray-600">We offer web and mobile app development, digital marketing, and Ux design to enhance online presence and customer engagement.</p>
      </div>

      <!-- Service Card 4 -->
      <div class="p-6 bg-white rounded-md shadow-md hover:shadow-lg">
        <div class="text-blue-500 mb-4">
          <svg class="w-12 h-12 mx-auto" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 16h-1v-4h-1m-1-4h1m-3 0h1m0 4h1m4-4h-1m0 4h-1m0-4h1m3 0h-1m0 4h-1" />
          </svg>
        </div>
        <h3 class="text-xl font-semibold">A.I/M.L</h3>
        <p class="mt-4 text-gray-600">We Delivers' intelligent algorithms for data analysis and automation, improving decision-making and optimizing processes across industries.</p>
      </div>
    </div>
  </div>
</div>



  
    <!-- Project Showcase Section -->
    <div class="py-16 bg-white">
  <div class="container mx-auto px-4 sm:px-6 lg:px-8 text-center">
    <h2 class="text-3xl md:text-4xl font-bold mb-10">Our Recent Projects</h2>
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6 lg:gap-8">
      
      <div class="bg-gray-100 rounded-lg shadow-lg overflow-hidden transform transition hover:scale-105 mx-2 lg:mx-0">
        <img src="assets/st.jpg" alt="Project 1" class="w-full h-64 object-cover">
        <div class="p-6">
          <h3 class="text-xl font-semibold">Tech Startup </h3>
          <p class="mt-4 text-gray-600">Designed a sleek, modern interface for a tech startup focused on AI solutions.</p>
          <a href="#" class="text-blue-500 hover:underline mt-4 block">View Case Study</a>
        </div>
      </div>
      
      <div class="bg-gray-100 rounded-lg shadow-lg overflow-hidden transform transition hover:scale-105 mx-2 lg:mx-0">
        <img src="assets/ecommerce.png" alt="Project 2" class="w-full h-64 object-cover">
        <div class="p-6">
          <h3 class="text-xl font-semibold">E-commerce Platform</h3>
          <p class="mt-4 text-gray-600">Developed a user-friendly e-commerce platform optimized for conversions.</p>
          <a href="#" class="text-blue-500 hover:underline mt-4 block">View Case Study</a>
        </div>
      </div>
      
      <div class="bg-gray-100 rounded-lg shadow-lg overflow-hidden transform transition hover:scale-105 mx-2 lg:mx-0">
        <img src="assets/ph.jpg" alt="Project 3" class="w-full h-64 object-cover">
        <div class="p-6">
          <h3 class="text-xl font-semibold">Mobile App Design</h3>
          <p class="mt-4 text-gray-600">Created a seamless mobile app experience for online learning.</p>
          <a href="#" class="text-blue-500 hover:underline mt-4 block">View Case Study</a>
        </div>
      </div>

    </div>
  </div>
</div>

<section class="flex flex-col-reverse md:flex-row items-center justify-center py-16 px-6 md:px-16 lg:px-32 bg-gray-100">
  <div class="md:w-1/2 lg:w-5/12 space-y-6 md:pr-10 text-center md:text-left">
    <h2 class="text-2xl md:text-3xl lg:text-4xl font-bold text-blue-500 leading-tight">
      Transforming Ideas into Reality
    </h2>
    <p class="text-lg text-gray-600">
      Harness the power of advanced technology solutions to enhance your business's efficiency, scalability,
       and growth. Together, we can transform your vision into reality through innovative strategies that keep you at the forefront of the digital landscape.
    </p>
    <button class="bg-blue-500 text-white px-6 py-3 rounded-md hover:bg-blue-600 transition duration-300">
      Learn More
    </button>
  </div>

  <!-- Image Section -->
  <div class="md:w-1/2 lg:w-5/12 mb-6 md:mb-0 flex justify-center">
    <img src="/assets/ai.jpg" alt="Tech Illustration" 
         class="w-full max-w-sm h-auto rounded-lg shadow-lg transform hover:scale-105 transition duration-300">
  </div>
</section>
  
      <!-- Features & Benefits Section -->
      <div class="py-16 bg-gray-900 text-white">
  <div class="container mx-auto text-center px-16"> <!-- Added padding -->
    <h2 class="text-3xl font-bold mb-8">Why Choose Us</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8"> <!-- Adjusted grid for larger screens -->
      <div class="p-6 bg-gray-800 rounded-md shadow-md">
        <h3 class="text-xl font-semibold">Innovative Solutions</h3>
        <p class="mt-4 text-gray-400">We stay ahead of the curve with the latest design and development trends.</p>
      </div>
      
      <div class="p-6 bg-gray-800 rounded-md shadow-md">
        <h3 class="text-xl font-semibold">Expert Team</h3>
        <p class="mt-4 text-gray-400">Our experienced professionals deliver quality services tailored to your needs.</p>
      </div>

      <div class="p-6 bg-gray-800 rounded-md shadow-md">
        <h3 class="text-xl font-semibold">Customer Focused</h3>
        <p class="mt-4 text-gray-400">We prioritize your satisfaction and work closely with you to achieve your goals.</p>
      </div>
      
      <!-- Add more features as needed -->
    </div>
  </div>
</div>
  





  
     
     
      
    </section>
  </template>
  
  <script setup>
  function subscribe() {
    // Handle newsletter subscription
    alert('Subscribed successfully!');
  }
  </script>
  
  <style scoped>
  /* Additional custom styles */
  </style>
  