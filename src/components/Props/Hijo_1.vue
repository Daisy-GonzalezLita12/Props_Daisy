<script setup>
import { ref } from 'vue'
defineProps({
  nombre: String, edad: String, carrera: String, direccion: String, telefono: String,
})
const count = ref(0)
</script>
<template>
    <h2 style="color:blueviolet">Soy el componente Hijo 1</h2>
    <h3 style="color:blueviolet">{{ nombre }}</h3>
    <h3 style="color:blueviolet">{{ edad }}</h3> 
    <h3 style="color:blueviolet">{{ carrera }}</h3>
    <h3 style="color:blueviolet">{{ direccion }}</h3>
    <h3 style="color:blueviolet">{{ telefono }}</h3>
</template>



