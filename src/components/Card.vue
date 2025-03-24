<template>
  <div class="container mt-5">
    <h2 class="text-center text-primary">Nuestra Filosofía</h2>
    <div class="row mt-4">
      <div class="col-md-4">
        <div class="card custom-card">
          <img src="https://img.freepik.com/vector-gratis/ilustracion-concepto-chef_114360-1734.jpg" class="card-img-top" alt="Misión">
          <div class="card-body text-center">
            <h5 class="card-title">Misión</h5>
            <p class="card-text">
              Brindar una experiencia culinaria única, resaltando los sabores auténticos de Tlaxiaco con ingredientes frescos y recetas tradicionales.
            </p>
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card custom-card">
          <img src="https://img.freepik.com/vector-gratis/ilustracion-concepto-restaurante_114360-1766.jpg" class="card-img-top" alt="Visión">
          <div class="card-body text-center">
            <h5 class="card-title">Visión</h5>
            <p class="card-text">
              Ser el restaurante de referencia en la región, reconocido por su calidad, calidez y compromiso con la gastronomía oaxaqueña.
            </p>
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card custom-card">
          <img src="https://img.freepik.com/vector-gratis/ilustracion-concepto-hospitalidad_114360-1684.jpg" class="card-img-top" alt="Valores">
          <div class="card-body text-center">
            <h5 class="card-title">Valores</h5>
            <p class="card-text">
              Compromiso con la calidad, respeto a la tradición, hospitalidad excepcional y amor por la gastronomía mexicana.
            </p>
          </div>
        </div>
      </div>
    </div>

    <h2 class="text-center text-primary mt-5">Nuestra Carta</h2>
    <div class="row mt-4">
      <div class="col-md-3">
        <div class="card custom-card">
          <img src="https://img.freepik.com/foto-gratis/hamburguesa-deliciosa_144627-41127.jpg" class="card-img-top" alt="Comida">
          <div class="card-body text-center">
            <h5 class="card-title">Comidas</h5>
            <button class="btn btn-warning">Ver más</button>
          </div>
        </div>
      </div>

      <div class="col-md-3">
        <div class="card custom-card">
          <img src="https://img.freepik.com/foto-gratis/deliciosa-bebida-refrescante-limonada_144627-18484.jpg" class="card-img-top" alt="Bebidas">
          <div class="card-body text-center">
            <h5 class="card-title">Bebidas</h5>
            <button class="btn btn-warning">Ver más</button>
          </div>
        </div>
      </div>

      <div class="col-md-3">
        <div class="card custom-card">
          <img src="https://img.freepik.com/foto-gratis/delicioso-postre-fresas-crema_144627-16013.jpg" class="card-img-top" alt="Postres">
          <div class="card-body text-center">
            <h5 class="card-title">Postres</h5>
            <button class="btn btn-warning">Ver más</button>
          </div>
        </div>
      </div>

      <div class="col-md-3">
        <div class="card custom-card">
          <img src="https://img.freepik.com/foto-gratis/nachos-salsa-guacamole-queso_1150-20619.jpg" class="card-img-top" alt="Snacks">
          <div class="card-body text-center">
            <h5 class="card-title">Snacks</h5>
            <button class="btn btn-warning">Ver más</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.custom-card {
  border-radius: 15px;
  box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.2);
}

.card img {
  border-top-left-radius: 15px;
  border-top-right-radius: 15px;
  height: 200px;
  object-fit: cover;
}

.card-title {
  font-weight: bold;
  color: #333;
}
</style>
