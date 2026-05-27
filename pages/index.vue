<script setup>
definePageMeta({
  layout: 'blank',
})

useHead({
  title: 'نه',
  link: [
    {
      rel: 'stylesheet',
      href: 'https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap',
    },
  ],
})
</script>

<template>
  <main class="nah-container">
    <div class="centered-text">
      <h1>نه</h1>
    </div>
  </main>
</template>

<style scoped>
.nah-container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
  font-family: 'Roboto', sans-serif;
  background-color: black;
}
.centered-text {
  text-align: center;
}
h1 {
  color: white;
  font-size: 1000%;
  margin: 0;
}
</style>
