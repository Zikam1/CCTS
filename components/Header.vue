<template>
  <header class="bg-white dark:bg-gray-900 shadow-md">
    <div class="container mx-auto px-4 py-4 flex justify-between items-center">
      <!-- Logo -->
      <div class="text-2xl font-bold text-gray-900 dark:text-white">
        <a href="/">Clarionconcept</a>
      </div>
      
      <!-- Navigation Links -->
      <nav class="hidden md:flex space-x-6">
        <a href="/" class="text-gray-600 dark:text-gray-300 hover:text-blue-500">Home</a>
        <a href="/projects" class="text-gray-600 dark:text-gray-300 hover:text-blue-500">Projects</a>
        <a href="/about" class="text-gray-600 dark:text-gray-300 hover:text-blue-500">About</a>
        <a href="/contact" class="text-gray-600 dark:text-gray-300 hover:text-blue-500">Contact</a>
      </nav>
      
      <!-- Actions -->
      <div class="flex items-center space-x-4">
        <!-- Dark Mode Toggle -->
        <button @click="toggleDarkMode" class="focus:outline-none">
          <svg v-if="isDarkMode" class="w-6 h-6 text-yellow-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 3v1m6.364 1.636l-.707-.707m4.243 4.243h-1M21 12h-1m-1.636 6.364l-.707.707m-4.243-4.243v1M12 21v1m-6.364-1.636l.707.707m-4.243-4.243h1M3 12h1m1.636-6.364l.707-.707M7.757 4.757l-.707.707M12 5a7 7 0 017 7h-1a6 6 0 00-6-6V5z" />
          </svg>
          <svg v-else class="w-6 h-6 text-gray-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 3v1m6.364 1.636l-.707-.707m4.243 4.243h-1M21 12h-1m-1.636 6.364l-.707.707m-4.243-4.243v1M12 21v1m-6.364-1.636l.707.707m-4.243-4.243h1M3 12h1m1.636-6.364l.707-.707M7.757 4.757l-.707.707M12 5a7 7 0 017 7h-1a6 6 0 00-6-6V5z" />
          </svg>
        </button>
        
        <!-- Search Icon -->
        <button class="text-gray-600 dark:text-gray-300 focus:outline-none">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-4.35-4.35m1.1-5.4a7.5 7.5 0 11-15 0 7.5 7.5 0 0115 0z"></path>
          </svg>
        </button>
        
        <!-- CTA Button -->
        <a href="/get-started" class="bg-blue-500 text-white px-4 py-2 rounded-md hover:bg-blue-600">Get Started</a>
      </div>
      
      <!-- Mobile Menu Button -->
      <button @click="isOpen = !isOpen" class="md:hidden text-gray-600 dark:text-gray-300 focus:outline-none">
        <svg v-if="!isOpen" class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
        </svg>
        <svg v-else class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
        </svg>
      </button>
    </div>
    
    <!-- Mobile Menu -->
    <div v-if="isOpen" class="md:hidden px-4 py-2 bg-white dark:bg-gray-900 space-y-2">
      <a href="/" class="block text-gray-600 dark:text-gray-300">Home</a>
      <a href="/projects" class="block text-gray-600 dark:text-gray-300">Projects</a>
      <a href="/about" class="block text-gray-600 dark:text-gray-300">About</a>
      <a href="/contact" class="block text-gray-600 dark:text-gray-300">Contact</a>
    </div>
  </header>
</template>

<script setup>
import { ref } from 'vue'

const isOpen = ref(false)
const isDarkMode = ref(false)

function toggleDarkMode() {
  isDarkMode.value = !isDarkMode.value
}
</script>
