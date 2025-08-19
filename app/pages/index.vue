<template>
  <div>
    <!-- Hero Section with Split Layout -->
    <section class="bg-gradient-to-br from-gray-50 to-white py-20 lg:py-32">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="grid lg:grid-cols-2 gap-12 items-center">
          <div>
            <h1 class="text-5xl lg:text-6xl font-bold text-gray-900 mb-6 leading-tight">
              Transform your business
              <span class="text-teal-600">automatically</span>
              with expert guidance.
            </h1>
            <p class="text-xl text-gray-600 mb-8 leading-relaxed">
              Strategic HR management, financial optimization, and career empowerment tools
              that scale with your business growth and professional aspirations.
            </p>
            <div class="flex flex-col sm:flex-row gap-4">
              <NuxtLink to="/contact"
                class="bg-teal-600 text-white px-8 py-4 rounded-lg font-semibold hover:bg-teal-700 transition-colors inline-flex items-center justify-center">
                Get Started
                <svg class="w-5 h-5 ml-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3">
                  </path>
                </svg>
              </NuxtLink>
              <NuxtLink to="/services"
                class="border border-gray-300 text-gray-700 px-8 py-4 rounded-lg font-semibold hover:bg-gray-50 transition-colors inline-flex items-center justify-center">
                Learn More
              </NuxtLink>
            </div>
          </div>

          <!-- Hero Visual -->
          <div class="relative">
            <div class="bg-white rounded-2xl shadow-2xl p-8 border border-gray-100">
              <div class="flex items-center justify-between mb-6">
                <div class="flex items-center space-x-3">
                  <div class="w-3 h-3 bg-red-400 rounded-full"></div>
                  <div class="w-3 h-3 bg-yellow-400 rounded-full"></div>
                  <div class="w-3 h-3 bg-green-400 rounded-full"></div>
                </div>
                <span class="text-sm text-gray-500">Dashboard</span>
              </div>

              <div class="space-y-4">
                <div class="bg-teal-600 text-white p-4 rounded-lg">
                  <div class="text-sm opacity-90">Total Growth</div>
                  <div class="text-2xl font-bold">৳ 1,876,580</div>
                  <div class="flex items-center mt-2">
                    <div class="w-8 h-8 bg-white bg-opacity-20 rounded flex items-center justify-center mr-3">
                      <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 20 20">
                        <path fill-rule="evenodd"
                          d="M3.293 9.707a1 1 0 010-1.414l6-6a1 1 0 011.414 0l6 6a1 1 0 01-1.414 1.414L11 5.414V17a1 1 0 11-2 0V5.414L4.707 9.707a1 1 0 01-1.414 0z"
                          clip-rule="evenodd"></path>
                      </svg>
                    </div>
                    <span class="text-sm">+24% this month</span>
                  </div>
                </div>

                <div class="grid grid-cols-2 gap-4">
                  <div class="bg-gray-50 p-4 rounded-lg">
                    <div class="text-sm text-gray-600">HR Efficiency</div>
                    <div class="text-xl font-semibold text-gray-900">94%</div>
                  </div>
                  <div class="bg-gray-50 p-4 rounded-lg">
                    <div class="text-sm text-gray-600">Client Success</div>
                    <div class="text-xl font-semibold text-gray-900">98%</div>
                  </div>
                </div>

                <div class="bg-teal-600 text-white p-4 rounded-lg text-center">
                  <div class="text-sm opacity-90 mb-2">Ready to optimize?</div>
                  <button class="bg-white text-teal-600 px-4 py-2 rounded font-medium text-sm w-full">
                    Start Now
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Trust Indicators -->
    <section class="py-12 bg-white border-b border-gray-100">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-8">
          <p class="text-sm text-gray-500 uppercase tracking-wide font-medium">Trusted by leading companies</p>
        </div>
        <div class="flex justify-center items-center space-x-12 opacity-60">
          <div class="text-2xl font-bold text-gray-400">TechCorp</div>
          <div class="text-2xl font-bold text-gray-400">InnovateLab</div>
          <div class="text-2xl font-bold text-gray-400">GrowthCo</div>
          <div class="text-2xl font-bold text-gray-400">ScaleUp</div>
        </div>
      </div>
    </section>

    <!-- Features Section -->
    <section class="py-20 bg-gray-50">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-16">
          <h2 class="text-4xl font-bold text-gray-900 mb-4">
            Experience that grows with your scale.
          </h2>
          <p class="text-xl text-gray-600 max-w-3xl mx-auto">
            Comprehensive solutions designed to streamline your business operations
            and accelerate professional growth at every stage.
          </p>
        </div>

        <div class="grid md:grid-cols-3 gap-8">
          <div class="bg-white p-8 rounded-xl border border-gray-100 hover:shadow-lg transition-shadow">
            <div class="w-12 h-12 bg-teal-100 rounded-lg flex items-center justify-center mb-6">
              <svg class="w-6 h-6 text-teal-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                  d="M12 4.354a4 4 0 110 5.292M15 21H3v-1a6 6 0 0112 0v1zm0 0h6v-1a6 6 0 00-9-5.197m13.5-9a2.5 2.5 0 11-5 0 2.5 2.5 0 015 0z">
                </path>
              </svg>
            </div>
            <h3 class="text-xl font-semibold text-gray-900 mb-3">HR Management</h3>
            <p class="text-gray-600 mb-4">
              Streamlined recruitment, compliance management, and workforce optimization
              with automated processes that save time and reduce costs.
            </p>
            <div class="text-sm text-gray-500">
              • Automated hiring workflows<br>
              • Compliance monitoring<br>
              • Performance analytics
            </div>
          </div>

          <div class="bg-white p-8 rounded-xl border border-gray-100 hover:shadow-lg transition-shadow">
            <div class="w-12 h-12 bg-teal-100 rounded-lg flex items-center justify-center mb-6">
              <svg class="w-6 h-6 text-teal-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                  d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z">
                </path>
              </svg>
            </div>
            <h3 class="text-xl font-semibold text-gray-900 mb-3">Financial Strategy</h3>
            <p class="text-gray-600 mb-4">
              Strategic account management with real-time insights, budget optimization,
              and comprehensive reporting for informed decision-making.
            </p>
            <div class="text-sm text-gray-500">
              • Real-time financial insights<br>
              • Budget optimization tools<br>
              • Strategic planning support
            </div>
          </div>

          <div class="bg-white p-8 rounded-xl border border-gray-100 hover:shadow-lg transition-shadow">
            <div class="w-12 h-12 bg-teal-100 rounded-lg flex items-center justify-center mb-6">
              <svg class="w-6 h-6 text-teal-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z">
                </path>
              </svg>
            </div>
            <h3 class="text-xl font-semibold text-gray-900 mb-3">Career Growth</h3>
            <p class="text-gray-600 mb-4">
              Comprehensive career guidance with personalized development plans,
              job placement assistance, and ongoing professional support.
            </p>
            <div class="text-sm text-gray-500">
              • Personalized career paths<br>
              • Job placement assistance<br>
              • Professional development
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Statistics Section -->
    <section class="py-20 bg-white">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-16">
          <p class="text-sm text-teal-600 font-semibold uppercase tracking-wide mb-2">Results</p>
          <h2 class="text-4xl font-bold text-gray-900">Why they prefer Corporate Assistant</h2>
        </div>

        <div class="grid md:grid-cols-2 gap-12 items-center">
          <div>
            <div class="text-6xl font-bold text-teal-600 mb-2">500+</div>
            <div class="text-xl text-gray-900 font-semibold mb-8">Businesses already growing with Corporate Assistant
            </div>

            <div class="space-y-6">
              <div class="flex items-center space-x-4">
                <div class="w-12 h-12 bg-teal-100 rounded-full flex items-center justify-center">
                  <svg class="w-6 h-6 text-teal-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                      d="M13 10V3L4 14h7v7l9-11h-7z"></path>
                  </svg>
                </div>
                <div>
                  <div class="font-semibold text-gray-900">Instant process optimization</div>
                  <div class="text-gray-600">Streamline operations from day one</div>
                </div>
              </div>

              <div class="flex items-center space-x-4">
                <div class="w-12 h-12 bg-teal-100 rounded-full flex items-center justify-center">
                  <svg class="w-6 h-6 text-teal-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                      d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                  </svg>
                </div>
                <div>
                  <div class="font-semibold text-gray-900">Proven growth strategies</div>
                  <div class="text-gray-600">Data-driven approaches that deliver results</div>
                </div>
              </div>
            </div>
          </div>

          <div class="bg-gray-50 p-8 rounded-2xl">
            <div class="text-center mb-6">
              <div class="text-sm text-gray-500 mb-2">Average client growth</div>
              <div class="text-4xl font-bold text-gray-900">৳ 1,876,580</div>
            </div>

            <!-- Simple chart representation -->
            <div class="h-48 bg-gradient-to-t from-teal-100 to-teal-50 rounded-lg flex items-end justify-center p-4">
              <div class="text-center">
                <div class="w-2 h-32 bg-teal-600 rounded-full mx-auto mb-2"></div>
                <div class="text-xs text-gray-600">Growth trajectory</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Dark CTA Section -->
    <section class="py-20 bg-slate-900 text-white">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-16">
          <h2 class="text-4xl font-bold mb-4">
            Maximize your returns with a strategy that generates results.
          </h2>
        </div>

        <div class="grid md:grid-cols-3 gap-8">
          <div class="text-center">
            <div class="w-16 h-16 bg-teal-600 rounded-full flex items-center justify-center mx-auto mb-4">
              <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                  d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 100 4m0-4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 100 4m0-4v2m0-6V4">
                </path>
              </svg>
            </div>
            <h3 class="text-xl font-semibold mb-2">Optimize your strategy</h3>
            <p class="text-gray-300">Get AI-powered insights to streamline your business operations and maximize
              efficiency.</p>
          </div>

          <div class="text-center">
            <div class="w-16 h-16 bg-teal-600 rounded-full flex items-center justify-center mx-auto mb-4">
              <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                  d="M7 16a4 4 0 01-.88-7.903A5 5 0 1115.9 6L16 6a5 5 0 011 9.9M9 19l3 3m0 0l3-3m-3 3V10"></path>
              </svg>
            </div>
            <h3 class="text-xl font-semibold mb-2">Transfer your processes</h3>
            <p class="text-gray-300">Seamlessly migrate your existing workflows with our expert guidance and support.
            </p>
          </div>

          <div class="text-center">
            <div class="w-16 h-16 bg-teal-600 rounded-full flex items-center justify-center mx-auto mb-4">
              <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                  d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z">
                </path>
              </svg>
            </div>
            <h3 class="text-xl font-semibold mb-2">Watch your growth accelerate</h3>
            <p class="text-gray-300">Monitor real-time progress with comprehensive analytics and performance tracking.
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- Success Metrics -->
    <section class="py-20 bg-white">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-16">
          <h2 class="text-4xl font-bold text-gray-900 mb-4">
            We've helped innovative companies
          </h2>
          <p class="text-xl text-gray-600">Transform their operations and accelerate growth</p>
        </div>

        <div class="grid md:grid-cols-3 gap-8 text-center">
          <div>
            <div class="text-5xl font-bold text-teal-600 mb-2">85%</div>
            <div class="text-lg font-semibold text-gray-900 mb-1">Efficiency Increase</div>
            <div class="text-gray-600">Average operational improvement</div>
          </div>

          <div>
            <div class="text-5xl font-bold text-teal-600 mb-2">250K</div>
            <div class="text-lg font-semibold text-gray-900 mb-1">Cost Savings</div>
            <div class="text-gray-600">Average annual savings per client</div>
          </div>

          <div>
            <div class="text-5xl font-bold text-teal-600 mb-2">15+</div>
            <div class="text-lg font-semibold text-gray-900 mb-1">Years of Experience</div>
            <div class="text-gray-600">Proven track record</div>
          </div>
        </div>
      </div>
    </section>

    <!-- Final CTA -->
    <section class="py-20 bg-slate-900 text-white">
      <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
        <h2 class="text-4xl font-bold mb-6">
          Ready to level up your business operations?
        </h2>
        <p class="text-xl text-gray-300 mb-8">
          Join hundreds of companies already transforming their growth trajectory.
        </p>
        <div class="flex flex-col sm:flex-row gap-4 justify-center">
          <NuxtLink to="/contact"
            class="bg-teal-600 text-white px-8 py-4 rounded-lg font-semibold hover:bg-teal-700 transition-colors">
            Get Started Today
          </NuxtLink>
          <NuxtLink to="/services"
            class="border border-gray-600 text-white px-8 py-4 rounded-lg font-semibold hover:bg-gray-800 transition-colors">
            Learn More
          </NuxtLink>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup>
import { useHead } from '#app';

// Page meta
useHead({
  title: 'Corporate Assistant - Transform Your Business Automatically',
  meta: [
    { name: 'description', content: 'Strategic HR management, financial optimization, and career empowerment tools that scale with your business growth. Join 500+ companies already transforming their operations.' }
  ]
})
</script>