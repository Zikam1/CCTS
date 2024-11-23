<template>
    <section class="bg-gray-50 py-16 px-4 md:px-16 lg:px-0">
      <div class="container max-w-screen-lg mx-auto flex flex-col md:flex-row items-center justify-between space-y-8 md:space-y-0">
        <!-- Left Image Section -->
        <div class="md:w-1/2 flex justify-center items-center">
          <img src="../assets/co.webp" alt="Person interacting with a contact form" class="w-full max-w-md object-cover rounded-md shadow-lg">
        </div>
  
        <!-- Right Form Section -->
        <div class="md:w-1/2 space-y-6 px-4 md:px-8 text-center md:text-left">
          <h2 class="text-3xl md:text-4xl text-gray-900 font-bold mb-6">We’d Love to Hear From You!</h2>
          <p class="text-gray-700 mb-6">
            If you have any questions, feedback, or inquiries, please don't hesitate to get in touch. Fill out the form below and we'll respond shortly.
          </p>
  
          <form action="#" method="POST" class="space-y-4">
            <div class="flex flex-col space-y-2">
              <label for="name" class="text-gray-700">Full Name</label>
              <input type="text" id="name" name="name" required class="px-4 py-2 border rounded-md w-full bg-white focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-offset-2" placeholder="Your Full Name">
            </div>
  
            <div class="flex flex-col space-y-2">
              <label for="email" class="text-gray-700">Email Address</label>
              <input type="email" id="email" name="email" required class="px-4 py-2 border rounded-md w-full bg-white focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-offset-2" placeholder="Your Email Address">
            </div>
  
            <div class="flex flex-col space-y-2">
              <label for="message" class="text-gray-700">Your Message</label>
              <textarea id="message" name="message" rows="5" required class="px-4 py-2 border rounded-md w-full bg-white focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-offset-2" placeholder="Write your message here"></textarea>
            </div>
  
            <div class="flex justify-center md:justify-start mt-4">
              <button type="submit" class="bg-blue-500 text-white px-6 py-3 rounded-md hover:bg-blue-600 focus:outline-none focus:ring-4 focus:ring-blue-400">
                Send Message
              </button>
            </div>
          </form>
        </div>
      </div>
    </section>
  </template>
  