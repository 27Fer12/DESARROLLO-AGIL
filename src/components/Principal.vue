<template>
  <div class="background-container d-flex justify-content-center align-items-center">
    <div class="content-container">
      <div class="text-section">
        <h1>"El Alma De Tlaxiaco"</h1>
        <p>Disfruta de la mejor comida con ingredientes frescos y recetas únicas.</p>
      </div>
      <div class="image-section">
        <img
          src="https://img.freepik.com/vector-gratis/diseno-carta-restaurante-vintage_23-2147491098.jpg"
          alt="Imagen de restaurante"
          class="restaurant-image"
        />
      </div>
    </div>
  </div>
</template>

<style scoped>
.background-container {
  width: 100%;
  height: 80vh;
  background: linear-gradient(to bottom, #f5e6ff, #d8a4d3);
  display: flex;
  justify-content: center;
  align-items: center;
}

.content-container {
  display: flex;
  align-items: center;
  gap: 40px;
}

.text-section {
  max-width: 400px;
  color: #5a189a;
  font-weight: bold;
}

.image-section {
  display: flex;
  justify-content: center;
}

.restaurant-image {
  max-width: 350px;
  border-radius: 10px;
}
</style>
