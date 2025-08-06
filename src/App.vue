<script setup>
import Json from './components/JSON.vue'
</script>

<template>
  <header>
  </header>

  <main>
    <Json />
  </main>
</template>

<style scoped>
body {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #ffffff;
  margin: 0;
}
main {
  padding: 20px;
  background-color: #ffffff;
}
header {
  background-color: #35495e;
  color: white;
  padding: 20px;
  text-align: center;
  font-size: 24px;
}
</style>
