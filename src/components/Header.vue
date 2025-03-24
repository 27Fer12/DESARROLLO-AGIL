<template>
  <header class="hero-section">
    <div class="container text-center">
      <h1 class="display-4 text-white">Bienvenidos a Nuestro Restaurante</h1>
      <p class="lead text-white">Disfruta de lo mejor de la gastronomía local, ¡te esperamos!</p>
      
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
.hero-section {
  background-image: url('https://img.freepik.com/vector-gratis/diseno-carta-restaurante-vintage_23-2147491098.jpg');
  background-size: 20%; /* Ajusta el tamaño de la imagen (más pequeña) */
  background-position: center;
  background-repeat: no-repeat; /* Evita que la imagen se repita */
  background-color:#5A189A; /* Fondo morado para el resto de la pantalla */
  height: 40vh; /* Ajusta la altura del header */
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: black;
  padding: 0 20px;
}

.hero-section .btn {
  margin-top: 20px;
}

.hero-section h1 {
  font-size: 3rem;
  font-weight: bold;
}

.hero-section p {
  font-size: 1.2rem;
  margin-top: 10px;
}
</style>
