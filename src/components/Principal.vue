<script setup>
//importacion del card principal
import CardPrincipal from './CardPrincipal.vue'
//importacion del primer card
import Card from './Card.vue'

</script>

<template>
  <div class="container">
    <h1 class="text-center">MASCOTAS</h1>
    
    <!-- Inicio del primer row -->
   <CardPrincipal />
    <!-- Cierre del primer row -->
    
    <!-- Inicio del segundo row -->
    <Card />
    <!-- Cierre del segundo row -->
  </div>
</template>

<style scoped>
/* Estilos específicos para este componente */
.container {
  padding: 20px;
}
</style>
