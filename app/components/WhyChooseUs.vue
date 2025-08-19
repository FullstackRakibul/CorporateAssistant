<template>
  <section class="py-20 bg-slate-50">
    <div class="container mx-auto px-4 max-w-6xl">
      <div class="text-center mb-16">
        <h2 class="text-3xl lg:text-4xl font-bold text-slate-900 mb-4">
          Why Choose Corporate Assistant?
        </h2>
        <p class="text-xl text-slate-600 max-w-3xl mx-auto">
          Our unique dual perspective and comprehensive approach set us apart
        </p>
      </div>

      <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
        <div v-for="feature in features" :key="feature.title" class="text-center">
          <div class="w-20 h-20 bg-white rounded-full flex items-center justify-center mx-auto mb-6 shadow-lg">
            <component :is="feature.icon" class="w-10 h-10 text-cyan-600" />
          </div>
          <h3 class="text-lg font-bold text-slate-900 mb-3">{{ feature.title }}</h3>
          <p class="text-slate-600">{{ feature.description }}</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import { ref } from 'vue'

const features = ref([
  {
    title: 'Holistic Approach',
    description: 'We understand both employer needs and individual aspirations, creating perfect matches.',
    icon: 'HolisticIcon'
  },
  {
    title: 'Client-Centric Solutions',
    description: 'Tailored strategies that address your unique challenges and goals.',
    icon: 'ClientIcon'
  },
  {
    title: 'Experienced Experts',
    description: 'Our team brings years of industry expertise across HR, finance, and career development.',
    icon: 'ExpertIcon'
  },
  {
    title: 'Proven Results',
    description: 'Track record of successful placements and business transformations.',
    icon: 'ResultsIcon'
  }
])
</script>