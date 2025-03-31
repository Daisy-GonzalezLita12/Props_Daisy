<script setup>
import { ref } from 'vue'
defineProps({
  nombre: String,
})
const count = ref(0)
</script>
<template>
  <h1>{{ nombre }}</h1> 
</template>


