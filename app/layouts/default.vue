<template>
  <div class="min-h-screen bg-white">
    <AppHeader />
    <main>
      <slot />
    </main>
    <AppFooter />
  </div>
</template>

<script setup>
// Default layout for Corporate Assistant Nuxt app
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700&family=Source+Sans+Pro:wght@400;500;600&display=swap');

body {
  font-family: 'Source Sans Pro', sans-serif;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: 'Playfair Display', serif;
}
</style>