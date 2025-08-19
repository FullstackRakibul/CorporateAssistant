<template>
  <header class="bg-white shadow-sm border-b border-gray-100 sticky top-0 z-50">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex justify-between items-center h-16">
        <!-- Logo -->
        <div class="flex items-center">
          <NuxtLink to="/" class="flex items-center space-x-3">
            <div
              class="w-10 h-10 bg-gradient-to-br from-slate-700 to-purple-700 rounded-lg flex items-center justify-center">
              <span class="text-white font-bold text-lg">CA</span>
            </div>
            <span class="text-xl font-serif font-semibold text-slate-800">Corporate Assistant</span>
          </NuxtLink>
        </div>

        <!-- Desktop Navigation -->
        <nav class="hidden md:flex items-center space-x-8">
          <NuxtLink to="/" class="text-slate-600 hover:text-purple-700 font-medium transition-colors">
            Home
          </NuxtLink>
          <NuxtLink to="/services" class="text-slate-600 hover:text-purple-700 font-medium transition-colors">
            Services
          </NuxtLink>
          <NuxtLink to="/about" class="text-slate-600 hover:text-purple-700 font-medium transition-colors">
            About
          </NuxtLink>
          <NuxtLink to="/testimonials" class="text-slate-600 hover:text-purple-700 font-medium transition-colors">
            Testimonials
          </NuxtLink>
          <NuxtLink to="/contact"
            class="bg-purple-700 text-white px-6 py-2 rounded-lg hover:bg-purple-800 transition-colors font-medium">
            Contact Us
          </NuxtLink>
        </nav>

        <!-- Mobile menu button -->
        <div class="md:hidden">
          <button @click="mobileMenuOpen = !mobileMenuOpen" class="text-slate-600 hover:text-slate-800">
            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
              <path v-if="!mobileMenuOpen" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                d="M4 6h16M4 12h16M4 18h16" />
              <path v-else stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
            </svg>
          </button>
        </div>
      </div>

      <!-- Mobile Navigation -->
      <div v-if="mobileMenuOpen" class="md:hidden py-4 border-t border-gray-100">
        <div class="flex flex-col space-y-4">
          <NuxtLink to="/" class="text-slate-600 hover:text-purple-700 font-medium">
            Home
          </NuxtLink>
          <NuxtLink to="/services" class="text-slate-600 hover:text-purple-700 font-medium">
            Services
          </NuxtLink>
          <NuxtLink to="/about" class="text-slate-600 hover:text-purple-700 font-medium">
            About
          </NuxtLink>
          <NuxtLink to="/testimonials" class="text-slate-600 hover:text-purple-700 font-medium">
            Testimonials
          </NuxtLink>
          <NuxtLink to="/contact"
            class="bg-purple-700 text-white px-6 py-2 rounded-lg hover:bg-purple-800 transition-colors font-medium inline-block text-center">
            Contact Us
          </NuxtLink>
        </div>
      </div>
    </div>
  </header>
</template>

<script setup>
import { ref } from 'vue'

const mobileMenuOpen = ref(false)
</script>