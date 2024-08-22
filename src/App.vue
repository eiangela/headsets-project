<script setup>
import HomeIndex from './pages/HomeIndex.vue'
import AppBar from './components/AppBar.vue'
</script>

<template>
  <v-app>
    <header>
      <AppBar />
    </header>

    <main>
      <HomeIndex />
    </main>
  </v-app>
</template>
