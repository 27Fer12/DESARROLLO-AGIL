<template>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg custom-navbar">
    <div class="container-fluid">
      <a class="navbar-brand text-white" href="#">Restaurante</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link text-white active" href="HelloWorld.vue">Inicio</a>
          </li>
          <li class="nav-item dropdown" @click="toggleDropdown('menuDia')">
            <a class="nav-link dropdown-toggle text-white" href="#" role="button">Menú del Día</a>
            <ul v-if="dropdowns.menuDia" class="dropdown-menu show">
              <li><a class="dropdown-item" href="HelloWorld.vue">Desayunos</a></li>
              <li><a class="dropdown-item" href="HelloWorld.vue">Comidas</a></li>
              <li><a class="dropdown-item" href="HelloWorld.vue">Cenas</a></li>
            </ul>
          </li>
          <li class="nav-item dropdown" @click="toggleDropdown('promociones')">
            <a class="nav-link dropdown-toggle text-white" href="#" role="button">Promociones</a>
            <ul v-if="dropdowns.promociones" class="dropdown-menu show">
              <li><a class="dropdown-item" href="HelloWorld.vue">2x1</a></li>
              <li><a class="dropdown-item" href="HelloWorld.vue">Descuentos</a></li>
              <li><a class="dropdown-item" href="HelloWorld.vue">Ofertas especiales</a></li>
            </ul>
          </li>
          <li class="nav-item dropdown" @click="toggleDropdown('categoriasMenu')">
            <a class="nav-link dropdown-toggle text-white" href="#" role="button">Categorías del Menú</a>
            <ul v-if="dropdowns.categoriasMenu" class="dropdown-menu show">
              <li><a class="dropdown-item" href="HelloWorld.vue">Comidas</a></li>
              <li><a class="dropdown-item" href="HelloWorld.vue">Bebidas</a></li>
              <li><a class="dropdown-item" href="HelloWorld.vue">Postres</a></li>
              <li><a class="dropdown-item" href="HelloWorld.vue">Snacks</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link text-white" href="#">Nosotros</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Contenido principal -->
  <div class="background-container d-flex justify-content-center align-items-center">
    <div class="content-container">
      <div class="text-section">
        <h1>"El Alma De Tlaxiaco"</h1>
        <p>Disfruta de la mejor comida con ingredientes frescos y recetas únicas.</p>
      </div>
      <div class="image-section">
        <img src="https://img.freepik.com/vector-gratis/diseno-carta-restaurante-vintage_23-2147491098.jpg?t=st=1742435995~exp=1742439595~hmac=6d2027b66006cbcb963d89f73f3ede7482f55c287aa3e1bef008464b7ded7024&w=1480" alt="Imagen de restaurante" class="restaurant-image" />
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="footer">
    <div class="container text-center">
      <p class="text-white">© 2025 Restaurante, Inc.</p>
    </div>
  </footer>
</template>

<script>
export default {
  data() {
    return {
      dropdowns: {
        menuDia: false,
        promociones: false,
        categoriasMenu: false
      }
    };
  },
  methods: {
    toggleDropdown(menu) {
      this.dropdowns[menu] = !this.dropdowns[menu];
    }
  }
};
</script>

<style scoped>
/* Estilos generales */
body {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
  margin: 0;
}

/* Navbar */
.custom-navbar {
  background-color: #5a189a; /* Morado intenso */
  padding: 10px;
}

/* Contenedor con color de fondo */
.background-container {
  width: 100%;
  height: 80vh;
  background: linear-gradient(to bottom, #f5e6ff, #d8a4d3); /* Degradado suave */
  display: flex;
  justify-content: center;
  align-items: center;
}

/* Contenedor de contenido principal */
.content-container {
  display: flex;
  align-items: center;
  gap: 40px;
}

/* Sección de texto */
.text-section {
  max-width: 400px;
  color: #5a189a;
  font-weight: bold;
}
.text-container {
    text-align: center; /* Centra el título */
}

.text-container h1 {
    font-size: 2rem;
    font-weight: bold;
}

.text-container p {
    text-align: justify; /* Justifica el texto */
    max-width: 500px; /* Limita el ancho para mejor lectura */
    margin: 0 auto; /* Centra el párrafo */
}


/* Sección de imagen */
.image-section {
  display: flex;
  justify-content: center;
}

.restaurant-image {
  max-width: 350px;
  border-radius: 10px;
}

/* Footer */
.footer {
  background-color: #3d0066; /* Vino oscuro */
  padding: 10px;
  margin-top: auto;
}
</style>
