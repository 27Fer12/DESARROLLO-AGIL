<template>
  <footer class="footer bg-dark text-white py-4">
    <div class="container text-center">
      <p>&copy; 2025 Restaurante. Todos los derechos reservadosa a Rosa Salazar Doroteo</p>
      <ul class="list-unstyled">
        <li><a href="#" class="text-white">Política de Privacidad</a></li>
        <li><a href="#" class="text-white">Términos y Condiciones</a></li>
        <li><a href="#" class="text-white">Direccion: Calle Centro 33, Heroica Ciudad de Tlaxiaco, Oaxaca</a></li>
        <li><a href="#" class="text-white">Contacto</a></li>
       
      </ul>
      <div class="social-icons">
        <a href="#" class="text-white me-3"><i class="bi bi-facebook"></i> Facebook</a>
        <a href="#" class="text-white me-3"><i class="bi bi-twitter"></i> Twitter</a>
        <a href="#" class="text-white"><i class="bi bi-instagram"></i> Instagram</a>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
.footer {
  background-color: #2C3E50; /* Gris oscuro */
}

.footer a {
  text-decoration: none;
}

.footer a:hover {
  color: #F39C12; /* Color dorado para el hover */
}

.social-icons a {
  font-size: 1.2rem;
  margin-right: 15px;
}

.social-icons i {
  margin-right: 5px;
}
</style>
