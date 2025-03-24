<template>
    <div class="background-container">
      <div class="container text-center">
        <!-- Título -->
        <p class="small text-uppercase text-muted mb-3">Nuestro Menú</p>
        <h2 class="display-4 fw-bold text-white mb-4">
          Disfruta nuestros
          <span class="text-info">Comidas, postres y bebidas</span>
        </h2>
  
        <!-- Sección de platillos principales -->
        <div class="row g-3">
          <div class="col-lg-4 col-md-6 col-sm-12" v-for="(categoria, index) in categorias" :key="index">
            <div class="card border-0 rounded-lg shadow-sm">
              <img :src="categoria.imagen" class="card-img-top plato-imagen" :alt="categoria.nombre" />
              <div class="card-body text-center">
                <h5 class="card-title text-light mb-2">{{ categoria.nombre }}</h5>
                <p class="card-text text-muted mb-2">{{ categoria.descripcion }}</p>
                <button class="btn btn-warning btn-sm" @click="toggleDesplegable(index)">
                  Ver opciones
                </button>
                
                <!-- Lista desplegable de platillos -->
                <div v-if="categoria.mostrar" class="desplegable">
                  <ul class="list-group mt-2">
                    <li class="list-group-item d-flex justify-content-between align-items-center" v-for="(plato, idx) in categoria.platillos" :key="idx">
                      {{ plato.nombre }} - <span class="text-info">{{ plato.precio }}$</span>
                      <button class="btn btn-sm btn-success" @click="agregarAlCarrito(plato)">+</button>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        categorias: [
          {
            nombre: "Comida",
            descripcion: "Platos principales con sabores exquisitos para todos los gustos.",
            imagen: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRNNvInvYHD4mfsNi4guywL5ov0XNJiwA0bMA&s",
            mostrar: false,
            platillos: [
              { nombre: "orden de tacos", precio: "80" },
              { nombre: "Hamburguesa clásica", precio: "95.00" },
              { nombre: "Pizza margarita", precio: "200" }
            ]
          },
          {
            nombre: "Postres",
            descripcion: "Deliciosos postres para cerrar con broche de oro.",
            imagen: "https://www.hogarmania.com/archivos/201612/postres-turron-blando-jijona-navidad-recetas-xl-416x236x80xX.jpg",
            mostrar: false,
            platillos: [
              { nombre: "Pastel de chocolate", precio: "20" },
              { nombre: "Flan napolitano", precio: "25" },
              { nombre: "Helado artesanal", precio: "30" }
            ]
          },
          {
            nombre: "Bebidas",
            descripcion: "Bebidas refrescantes y cócteles perfectos para acompañar tu comida.",
            imagen: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRz5JjJJb23ItonWfGjci0p02YR7CmTdxOfuw&s",
            mostrar: false,
            platillos: [
              { nombre: "Refrescos", precio: "25" },
              { nombre: "Jugo natural", precio: "30" },
              { nombre: "Margarita", precio: "50" }
            ]
          }
        ]
      };
    },
    methods: {
      toggleDesplegable(index) {
        this.categorias[index].mostrar = !this.categorias[index].mostrar;
      },
      agregarAlCarrito(plato) {
        alert(`Añadido al carrito: ${plato.nombre}`);
      }
    }
  };
  </script>
  
  <style scoped>
  .background-container {
    width: 100%;
    padding: 80px 20px;
    background: #2a1a72;
    font-family: 'Poppins', sans-serif;
    min-height: 100vh;
  }
  
  .plato-imagen {
    height: 180px;
    object-fit: cover;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(255, 255, 255, 0.3);
  }
  
  h2 {
    color: #ffffff;
    margin-bottom: 20px;
  }
  
  .text-info {
    font-size: 1.2rem;
    font-weight: bold;
    color: #f39c12;
  }
  
  .btn-warning {
    background-color: #f39c12;
    border: none;
    color: #fff;
    padding: 10px 20px;
    border-radius: 5px;
    transition: background-color 0.3s ease;
  }
  
  .btn-warning:hover {
    background-color: #e67e22;
  }
  
  .card {
    border-radius: 15px;
    transition: transform 0.3s ease-in-out;
  }
  
  .card:hover {
    transform: translateY(-8px);
  }
  
  .list-group-item {
    background: #3a2a92;
    color: white;
    border: none;
  }
  
  .btn-success {
    background-color: #28a745;
    border: none;
    padding: 5px 10px;
    font-size: 0.8rem;
  }
  
  .btn-success:hover {
    background-color: #218838;
  }
  </style>