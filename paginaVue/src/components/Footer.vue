<template>
    <footer class="bg-dark text-light pt-5 pb-3 mt-5">
      <div class="container">
        <div class="row">
          <!-- Información del Restaurante -->
          <div class="col-md-3 mb-4">
            <h5>Mi Restaurante</h5>
            <p><i class="fas fa-map-marker-alt"></i> Calle Ficticia #123, Heroica ciudad de Tlaxiaco</p>
            <p><i class="fas fa-phone"></i> +1 (234) 567-890</p>
            <p><i class="fas fa-clock"></i> Lunes - Domingo: 10:00 AM - 10:00 PM</p>
          </div>
  
       
          <div class="col-md-3 mb-4">
            <h5>Menú</h5>
            <ul class="list-unstyled">
              <li><a href="/platos-principales" class="text-light">Platos Principales</a></li>
              <li><a href="/postres" class="text-light">Postres</a></li>
              <li><a href="/bebidas" class="text-light">Bebidas</a></li>
              <li><a href="/promociones" class="text-light">Promociones</a></li>
            </ul>
          </div>
  
          <!-- Conéctate -->
          <div class="col-md-3 mb-4">
            <h5>Conéctate</h5>
            <ul class="list-unstyled">
              <li><a href="/reserva" class="text-light">Reserva Online</a></li>
              <li><a href="/contacto" class="text-light">Contáctanos</a></li>
              <li><a href="/nosotros" class="text-light">Sobre Nosotros</a></li>
              <li><a href="/politica-privacidad" class="text-light">Política de Privacidad</a></li>
            </ul>
          </div>
  
          <!-- Redes Sociales -->
          <div class="col-md-3 mb-4">
            <h5>Síguenos</h5>
            <ul class="list-unstyled d-flex">
              <li class="me-3"><a href="https://facebook.com/miRestaurante" class="text-light" target="_blank"><i class="fab fa-facebook-f"></i></a></li>
              <li class="me-3"><a href="https://instagram.com/miRestaurante" class="text-light" target="_blank"><i class="fab fa-instagram"></i></a></li>
              <li><a href="https://twitter.com/miRestaurante" class="text-light" target="_blank"><i class="fab fa-twitter"></i></a></li>
            </ul>
          </div>
        </div>
  
        <!-- Derechos Reservados -->
        <div class="row mt-4">
          <div class="col text-center">
            <p class="small text-muted">© 2025 Mi Restaurante. Todos los derechos reservados Fernanda Ruiz Heras.</p>
          </div>
        </div>
      </div>
    </footer>
  </template>
  
  <style scoped>
  .footer {
    background-color: #121212;
    color: #ffffff;
  }
  
  .footer h5 {
    font-size: 1.1rem;
    color: #e0e0e0;
    margin-bottom: 15px;
  }
  
  .footer a {
    color: #b0b0b0;
    font-size: 0.9rem;
    text-decoration: none;
  }
  
  .footer a:hover {
    color: #f1c40f;
    text-decoration: underline;
  }
  
  .footer .fab {
    font-size: 1.2rem;
  }
  
  .footer .list-unstyled li {
    margin-bottom: 10px;
  }
  
  .footer .list-unstyled {
    padding-left: 0;
  }
  
  .footer .row {
    margin-bottom: 10px;
  }
  
  .footer .d-flex li {
    display: inline;
  }
  
  .footer .text-muted {
    font-size: 0.8rem;
  }
  </style>
  