<script setup>
import { ref } from 'vue'
import Hijo1 from './Hijo1.vue'
import Hijo2 from './Hijo2.vue'
const props = defineProps({
  nombre: String,
})
const count = ref(0)
</script>
<template>
    <div class="container">
        <!-- Título -->
        <h1>Soy el componente padre</h1>
        <!-- Se manda a traer el componente el componente "Hijo1" y se le asigna una edad-->
         <Hijo1 class="mt-4" edad="10"/>
        <!-- Se manda a traer el componente el componente "Hijo2" y se le asigna una edad-->
         <Hijo2 class="mt-4" edad="4"/>
    </div>
   </template>


