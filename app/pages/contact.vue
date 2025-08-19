<template>
  <div>
    <!-- Hero Section -->
    <section class="bg-gradient-to-br from-slate-50 to-slate-100 py-16">
      <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
        <h1 class="text-4xl font-bold text-slate-900 mb-6 font-serif">Contact Us</h1>
        <p class="text-xl text-slate-600">
          Ready to transform your business or career? We'd love to hear from you.
        </p>
      </div>
    </section>

    <!-- Contact Form & Info -->
    <section class="py-16 bg-white">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="grid lg:grid-cols-2 gap-12">

          <!-- Contact Form -->
          <div>
            <h2 class="text-2xl font-bold text-slate-900 mb-6 font-serif">Send Us a Message</h2>
            <form class="space-y-6">
              <div class="grid md:grid-cols-2 gap-6">
                <div>
                  <label for="firstName" class="block text-sm font-medium text-slate-700 mb-2">First Name</label>
                  <input type="text" id="firstName" name="firstName"
                    class="w-full px-4 py-3 border border-slate-300 rounded-lg focus:ring-2 focus:ring-purple-500 focus:border-transparent"
                    required>
                </div>
                <div>
                  <label for="lastName" class="block text-sm font-medium text-slate-700 mb-2">Last Name</label>
                  <input type="text" id="lastName" name="lastName"
                    class="w-full px-4 py-3 border border-slate-300 rounded-lg focus:ring-2 focus:ring-purple-500 focus:border-transparent"
                    required>
                </div>
              </div>

              <div>
                <label for="email" class="block text-sm font-medium text-slate-700 mb-2">Email Address</label>
                <input type="email" id="email" name="email"
                  class="w-full px-4 py-3 border border-slate-300 rounded-lg focus:ring-2 focus:ring-purple-500 focus:border-transparent"
                  required>
              </div>

              <div>
                <label for="phone" class="block text-sm font-medium text-slate-700 mb-2">Phone Number</label>
                <input type="tel" id="phone" name="phone"
                  class="w-full px-4 py-3 border border-slate-300 rounded-lg focus:ring-2 focus:ring-purple-500 focus:border-transparent">
              </div>

              <div>
                <label for="subject" class="block text-sm font-medium text-slate-700 mb-2">Subject</label>
                <select id="subject" name="subject"
                  class="w-full px-4 py-3 border border-slate-300 rounded-lg focus:ring-2 focus:ring-purple-500 focus:border-transparent"
                  required>
                  <option value="">Select a service</option>
                  <option value="hr-management">HR Management Services</option>
                  <option value="account-strategy">Account Management Strategy</option>
                  <option value="career-guidance">Career Guidance & Job Placement</option>
                  <option value="general">General Inquiry</option>
                </select>
              </div>

              <div>
                <label for="message" class="block text-sm font-medium text-slate-700 mb-2">Message</label>
                <textarea id="message" name="message" rows="6"
                  class="w-full px-4 py-3 border border-slate-300 rounded-lg focus:ring-2 focus:ring-purple-500 focus:border-transparent"
                  placeholder="Tell us about your needs and how we can help..." required></textarea>
              </div>

              <button type="submit"
                class="w-full bg-purple-600 text-white px-6 py-3 rounded-lg font-semibold hover:bg-purple-700 transition-colors">
                Send Message
              </button>
            </form>
          </div>

          <!-- Contact Information -->
          <div>
            <h2 class="text-2xl font-bold text-slate-900 mb-6 font-serif">Get in Touch</h2>
            <div class="space-y-8">

              <!-- Contact Details -->
              <div class="space-y-6">
                <div class="flex items-start">
                  <div class="w-12 h-12 bg-purple-100 rounded-lg flex items-center justify-center mr-4 flex-shrink-0">
                    <svg class="w-6 h-6 text-purple-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                        d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z">
                      </path>
                    </svg>
                  </div>
                  <div>
                    <h3 class="font-semibold text-slate-900 mb-1">Phone</h3>
                    <p class="text-slate-600">For Business Inquiries: +880 1581 500678 </p>
                    <p class="text-slate-600">For Job Seekers: +88 01717 599528</p>
                  </div>
                </div>

                <div class="flex items-start">
                  <div class="w-12 h-12 bg-purple-100 rounded-lg flex items-center justify-center mr-4 flex-shrink-0">
                    <svg class="w-6 h-6 text-purple-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                        d="M3 8l7.89 4.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z">
                      </path>
                    </svg>
                  </div>
                  <div>
                    <h3 class="font-semibold text-slate-900 mb-1">Email</h3>
                    <p class="text-slate-600">rakibul.it@hameemgroup.com</p>
                    <p class="text-slate-600">rakibul.cse.47@gmail.com</p>
                  </div>
                </div>

                <div class="flex items-start">
                  <div class="w-12 h-12 bg-purple-100 rounded-lg flex items-center justify-center mr-4 flex-shrink-0">
                    <svg class="w-6 h-6 text-purple-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                        d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z">
                      </path>
                    </svg>
                  </div>
                  <div>
                    <h3 class="font-semibold text-slate-900 mb-1">Office Address</h3>
                    <p class="text-slate-600">123 Business District<br>Suite 456<br>New York, NY 10001</p>
                  </div>
                </div>

                <div class="flex items-start">
                  <div class="w-12 h-12 bg-purple-100 rounded-lg flex items-center justify-center mr-4 flex-shrink-0">
                    <svg class="w-6 h-6 text-purple-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                        d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                        d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path>
                    </svg>
                  </div>
                  <div>
                    <h3 class="font-semibold text-slate-900 mb-1">Business Hours</h3>
                    <p class="text-slate-600">Monday - Friday: 9:00 AM - 6:00 PM</p>
                    <p class="text-slate-600">Saturday: 10:00 AM - 4:00 PM</p>
                    <p class="text-slate-600">Sunday: Closed</p>
                  </div>
                </div>
              </div>

              <!-- Social Media -->
              <div>
                <h3 class="font-semibold text-slate-900 mb-4">Follow Us</h3>
                <div class="flex space-x-4">
                  <a href="#"
                    class="w-10 h-10 bg-purple-100 rounded-lg flex items-center justify-center hover:bg-purple-200 transition-colors">
                    <svg class="w-5 h-5 text-purple-600" fill="currentColor" viewBox="0 0 20 20">
                      <path fill-rule="evenodd"
                        d="M16.338 16.338H13.67V12.16c0-.995-.017-2.277-1.387-2.277-1.39 0-1.601 1.086-1.601 2.207v4.248H8.014v-8.59h2.559v1.174h.037c.356-.675 1.227-1.387 2.526-1.387 2.703 0 3.203 1.778 3.203 4.092v4.711zM5.005 6.575a1.548 1.548 0 11-.003-3.096 1.548 1.548 0 01.003 3.096zm-1.337 9.763H6.34v-8.59H3.667v8.59zM17.668 1H2.328C1.595 1 1 1.581 1 2.298v15.403C1 18.418 1.595 19 2.328 19h15.34c.734 0 1.332-.582 1.332-1.299V2.298C19 1.581 18.402 1 17.668 1z"
                        clip-rule="evenodd"></path>
                    </svg>
                  </a>
                  <a href="#"
                    class="w-10 h-10 bg-purple-100 rounded-lg flex items-center justify-center hover:bg-purple-200 transition-colors">
                    <svg class="w-5 h-5 text-purple-600" fill="currentColor" viewBox="0 0 20 20">
                      <path
                        d="M6.29 18.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0020 3.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.073 4.073 0 01.8 7.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 010 16.407a11.616 11.616 0 006.29 1.84">
                      </path>
                    </svg>
                  </a>
                  <a href="#"
                    class="w-10 h-10 bg-purple-100 rounded-lg flex items-center justify-center hover:bg-purple-200 transition-colors">
                    <svg class="w-5 h-5 text-purple-600" fill="currentColor" viewBox="0 0 20 20">
                      <path fill-rule="evenodd"
                        d="M20 10.5a9.5 9.5 0 10-11 9.4v-6.6h-2.3v-2.8h2.3V8.4c0-2.3 1.4-3.6 3.5-3.6 1 0 2.1.2 2.1.2v2.3h-1.2c-1.2 0-1.5.7-1.5 1.5v1.8h2.7l-.4 2.8h-2.3v6.6A9.5 9.5 0 0020 10.5z"
                        clip-rule="evenodd"></path>
                    </svg>
                  </a>
                </div>
              </div>

              <!-- Call to Action -->
              <div class="bg-slate-50 p-6 rounded-xl">
                <h3 class="font-semibold text-slate-900 mb-2">Ready to Get Started?</h3>
                <p class="text-slate-600 mb-4">Schedule a free consultation to discuss your specific needs and how we
                  can help.</p>
                <button
                  class="bg-purple-600 text-white px-6 py-2 rounded-lg font-semibold hover:bg-purple-700 transition-colors">
                  Schedule Consultation
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup>

useHead({
  title: 'Contact Us - Corporate Assistant',
  meta: [
    { name: 'description', content: 'Get in touch with Corporate Assistant for HR management, account strategy, and career guidance services. Contact us today for a free consultation.' }
  ]
})
</script>