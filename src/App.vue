<script setup>
import { ref } from 'vue'
const brand = ref('🏢 Company Directory')
</script>

<template>
  <h1>{{ brand }}</h1>
</template>

<script setup>
import NavBar from './components/NavBar.vue'
</script>

<template>
  <NavBar />
  <h1>Main Content</h1>
</template>
