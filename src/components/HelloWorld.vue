<script setup>
import { ref } from 'vue'

const bienvenida = ref("Bienvenidos a la seccion de condicionales")
const nombre = ref ("Maribel")
const apellidos = ref ("Santiago Bautista" )
// defineProps({
//   msg: String,
// })

</script>

<template>
 <h2>{{bienvenida}}</h2>


</template>

<style scoped>

</style>
