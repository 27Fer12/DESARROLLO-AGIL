<template>
  <div class="row mt-4">
    <div class="col-md-4">
      <div class="card" style="width: 18rem; background-color: #2C3E50; color: white; border-radius: 10px;">
        <img src="https://imgs.search.brave.com/gF1SDPHYC3pPOHMqcCFTdczmIjFX289D6UqqyX6E2UI/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9pbWct/Z2xvYmFsLmNwY2Ru/LmNvbS9yZWNpcGVz/L2Q5Mzg1YTAyZjlj/OGM0NDAvMzAweDIy/MGNxNzAvYWd1YS1m/cmVzY2EtZGUtcGlu/YS1jb24tZXNwaW5h/Y2FzLWZvdG8tcHJp/bmNpcGFsLmpwZw" class="card-img-top" alt="Restaurante">
        <div class="card-body text-center">
          <p class="card-text">Disfruta de una experiencia gastronómica única, con sabores auténticos y un ambiente refinado.</p>
          <button class="btn btn-light">Ver Menú</button>
        </div>
      </div>
    </div>

    <div class="col-md-4">
      <div class="card" style="width: 18rem; background-color: #2C3E50; color: white; border-radius: 10px;">
        <img src="https://imgs.search.brave.com/MNgikA-MIbN6BLXHO3JCjM4a73gtfDaEXScl7JyEtA0/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9jb21l/ZGVyYS5jb20vd3At/Y29udGVudC91cGxv/YWRzL3NpdGVzLzkv/MjAxNy8wNi9yZWNl/dGFzLWRlLWNvbWlk/YS1tZXhpY2FuYS5q/cGc_cmVzaXplPTY3/NSwzODAmcXVhbGl0/eT04MA" class="card-img-top" alt="Comida Gourmet">
        <div class="card-body text-center">
          <p class="card-text">Sabores refinados que invitan a ser descubiertos. Cada plato es una obra de arte.</p>
          <button class="btn btn-light">Descubre nuestro menú</button>
        </div>
      </div>
    </div>

    <div class="col-md-4">
      <div class="card" style="width: 18rem; background-color: #2C3E50; color: white; border-radius: 10px;">
        <img src="https://imgs.search.brave.com/sWS6oJvyzifSS1XEmxHojq8QwUpG65BVD4sqB4T0Cj0/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9nb2dv/ZXNwYW5hLmNvbS93/cC1jb250ZW50L3Vw/bG9hZHMvMjAyMy8x/MC80LTEwMjR4NTY5/LmpwZw" class="card-img-top" alt="Ambiente elegante">
        <div class="card-body text-center">
          <p class="card-text">Ambiente elegante para tus momentos más especiales. Disfruta de la mejor compañía en un lugar único.</p>
          <button class="btn btn-light">Reservar Mesa</button>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
  .row {
    background-color: #34495E; /* Fondo gris oscuro para crear un ambiente serio */
    padding: 30px;
  }

  .card {
    background-color: #502c4e; /* Fondo de tarjeta oscuro */
    color: white; /* Texto blanco para un contraste elegante */
    border-radius: 10px; /* Bordes redondeados para un look más suave */
  }

  .card-img-top {
    height: 200px; /* Limita la altura de las imágenes para mantener la proporción */
    object-fit: cover; /* Hace que la imagen se recorte sin perder proporciones */
  }

  .card-body {
    padding: 20px;
  }

  .btn-light {
    background-color: #ECF0F1; /* Color gris claro para botones */
    color: #34495E; /* Texto oscuro para los botones */
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    text-transform: uppercase;
  }

  .btn-light:hover {
    background-color: #BDC3C7; /* Color más oscuro cuando se pasa el mouse sobre el botón */
  }
</style>
