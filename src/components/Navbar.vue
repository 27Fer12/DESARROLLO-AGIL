<template>
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
            <a class="nav-link text-white active" href="#">Inicio</a>
          </li>
          <li class="nav-item dropdown" @click="toggleDropdown('menuDia')">
            <a class="nav-link dropdown-toggle text-white" href="#" role="button">Menú del Día</a>
            <ul v-if="dropdowns.menuDia" class="dropdown-menu show">
              <li><a class="dropdown-item" href="#">Desayunos</a></li>
              <li><a class="dropdown-item" href="#">Comidas</a></li>
              <li><a class="dropdown-item" href="#">Cenas</a></li>
            </ul>
          </li>
          <li class="nav-item dropdown" @click="toggleDropdown('promociones')">
            <a class="nav-link dropdown-toggle text-white" href="#" role="button">Promociones</a>
            <ul v-if="dropdowns.promociones" class="dropdown-menu show">
              <li><a class="dropdown-item" href="#">2x1</a></li>
              <li><a class="dropdown-item" href="#">Descuentos</a></li>
              <li><a class="dropdown-item" href="#">Ofertas especiales</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link text-white" href="#">Nosotros</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  data() {
    return {
      dropdowns: {
        menuDia: false,
        promociones: false
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
.custom-navbar {
  background-color: #5a189a;
  padding: 10px;
}
</style>
