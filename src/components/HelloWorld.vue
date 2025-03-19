<script setup>
</script>

<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Navbar</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Dropdown
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
        </li>
      </ul>
      <form class="d-flex">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form>
    </div>
  </div>
</nav>
  <div class="container">
    <h1 class="text-center">RESTAURANTE</h1>
    
    <!-- Inicio del primer row (con 3 tarjetas alineadas) -->
    <div class="row">
      <!-- Cuadro de BEBIDA 1 -->
      <div class="col-md-4">
        <div class="card">
          <div class="card-header">
            <h6>BEBIDA</h6>
          </div>
          <div class="card-body"></div>
          <p class="card-text">Sabores irresistibles, hechos con pasión..</p>
        </div>
      </div>

      <!-- Cuadro de POSTRE -->
      <div class="col-md-4">
        <div class="card">
          <div class="card-header">
            <h6>POSTRE</h6>
          </div>
          <div class="card-body"></div>
          <p class="card-text">El toque dulce que tu día necesitaba.</p>
        </div>
      </div>

      <!-- Cuadro de BEBIDA 2 -->
      <div class="col-md-4">
        <div class="card">
          <div class="card-header">
            <h6>BEBIDA</h6>
          </div>
          <div class="card-body"></div>
          <p class="card-text">Refresca tu día con nuestras bebidas exclusivas.</p>
        </div>
      </div>
    </div>
    <!-- Cierre del primer row -->

    <!-- Inicio del segundo row (con 3 tarjetas de ejemplo de gatitos) -->
    <div class="row mt-4">
      <div class="col-md-4">
        <div class="card" style="width: 18rem;">
          <img src="https://imgs.search.brave.com/KD5vHtvYgLx3a6vymN2ZfHY3v34P5MjZXyfpeHsvmpg/rs:fit:500:0:0:0/g:ce/aHR0cHM6Ly9tYm1h/cmNvYmV0ZXRhLmNv/bS93cC1jb250ZW50/L3VwbG9hZHMvMjAy/NC8wOC9JTUdfMzc5/MC1jb3BpYS53ZWJw" class="card-img-top" alt="Gato animado">
          <div class="card-body text-center">
            <p class="card-text">La comida que hace sonreír a tu paladar.</p>
            <button class="btn-warning">Comida</button>
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card" style="width: 18rem;">
          <img src="https://imgs.search.brave.com/RAUteC_pHWsrvs1hG_9lF12FtLSrsAPolmzXSgw4Jyk/rs:fit:500:0:0:0/g:ce/aHR0cHM6Ly9jb250/ZW50LmVsbXVlYmxl/LmNvbS9tZWRpby8y/MDIzLzAzLzE1L3Bv/c3RyZXNfMjZiMTU3/YzBfMDA1NDM4MzBf/MjMwMzE1MTE0OTUy/XzkwMHg5MDAuanBn" class="card-img-top" alt="Gato animado">
          <div class="card-body text-center">
            <p class="card-text">Bebidas que te llenan de energía y sabor..</p>
            <button class="btn-warning">Postre</button>
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card" style="width: 18rem;">
          <img src="https://imgs.search.brave.com/hWOMr9SKwBw_v28DXaUI_rj6yo-cnLnZUcDbBAaOtQs/rs:fit:500:0:0:0/g:ce/aHR0cHM6Ly93d3cu/ZmluZWRpbmluZ2xv/dmVycy5jb20vZXMv/c2l0ZXMvZy9maWxl/cy94a25mZGsxNzA2/L2ZpbGVzLzIwMjIt/MDYvY28lQ0MlODFj/dGVsZXMtZGUtZnJ1/dGFzLW1vaml0by1m/cnV0YS1wYXNpb24l/QzIlQTlpU3RvY2su/anBn" class="card-img-top" alt="Gato animado">
          <div class="card-body text-center">
            <p class="card-text">Déjate consentir con el postre de tus sueños..</p>
            <button class="btn-warning">Bebida</button>
          </div>
        </div>
      </div>
    </div>
    <!-- Cierre del segundo row -->
    <div class="container">
  <footer class="py-3 my-4">
    <ul class="nav justify-content-center border-bottom pb-3 mb-3">
      <li class="nav-item"><a href="#" class="nav-link px-2 text-muted">Home</a></li>
      <li class="nav-item"><a href="#" class="nav-link px-2 text-muted">Features</a></li>
      <li class="nav-item"><a href="#" class="nav-link px-2 text-muted">Pricing</a></li>
      <li class="nav-item"><a href="#" class="nav-link px-2 text-muted">FAQs</a></li>
      <li class="nav-item"><a href="#" class="nav-link px-2 text-muted">About</a></li>
    </ul>
    <p class="text-center text-muted">© 2022 Company, Inc</p>
  </footer>
</div>
  </div>
</template>

<style scoped>
/* Estilos específicos para este componente */
.container {
  padding: 20px;
}
</style>
