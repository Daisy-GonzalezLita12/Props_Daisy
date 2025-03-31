<script setup>
import { ref } from 'vue'
defineProps({
  nombre: String, edad: String, carrera: String, direccion: String, telefono: String,
})
const count = ref(0)
</script>
<template>
    <h2 style="color:coral">Soy el componente Hijo 2</h2>
    <h3 style="color:coral">{{ nombre }}</h3>
    <h3 style="color:coral">{{ edad }}</h3> 
    <h3 style="color:coral">{{ carrera }}</h3>
    <h3 style="color:coral">{{ direccion }}</h3>
    <h3 style="color:coral">{{ telefono }}</h3>
</template>


