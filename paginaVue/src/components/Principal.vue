<template>
    <div class="background-container d-flex justify-content-center align-items-center">
      <div class="container">
        <div class="row align-items-center">
          <!-- Sección de imagen -->
          <div class="col-md-5 text-center">
            <div class="image-container">
              <img
                src="https://i.pinimg.com/originals/70/c6/41/70c641d7b3a1fedbc6cda02cca3e1722.gif"
                alt="Restaurante"
                class="restaurant-image"
              />
              <div class="experience-badge">"Menos dudas, más certezas."</div>
            </div>
          </div>
  
          <!-- Sección de texto -->
          <div class="col-md-7">
            <p class="small text-uppercase text-muted">Acerca de Nosotros</p>
            <h1 class="display-5 fw-bold text-white">
              Nuestro compromiso con la 
              <span class="text-warning">autenticidad</span> & 
              <span class="text-warning">excelencia</span>
            </h1>
            <p class="text-light">
              Cada platillo que creamos es una celebración de conexión, elaborado con pasión e inspirado en una fusión de sabores. 
              Te invitamos a un espacio acogedor donde cada bocado despierta alegría y cada momento se convierte en un recuerdo inolvidable.
            </p>
  
            <ul class="list-unstyled text-light">
              <li>✅ Ingredientes frescos y de origen local</li>
              <li>✅ Opciones vegetarianas y aptas para dietas especiales</li>
              <li>✅ Maridajes exquisitos y sabores únicos</li>
            </ul>
  
            <div class="mt-4">
              <button class="btn btn-warning btn-lg me-3">Ordena Ahora</button>
              <button class="btn btn-outline-light btn-lg">Conoce Más →</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <style scoped>
  /* Fondo oscuro elegante */
  .background-container {
    width: 100%;
    height: 100vh;
    background: #121212;
    display: flex;
    align-items: center;
    padding: 40px 20px;
  }
  
  /* Imagen con efecto circular */
  .image-container {
    position: relative;
    display: inline-block;
  }
  
  .restaurant-image {
    width: 100%;
    max-width: 350px;
    border-radius: 50%;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
  }
  
  /* Badge de experiencia */
  .experience-badge {
    position: absolute;
    top: 10%;
    left: 50%;
    transform: translateX(-50%);
    background: rgba(255, 204, 0, 0.9);
    color: #000;
    padding: 8px 12px;
    border-radius: 20px;
    font-weight: bold;
    font-size: 14px;
  }
  </style>
  