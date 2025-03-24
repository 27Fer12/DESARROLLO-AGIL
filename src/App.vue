<template>
  <Navbar />
  <Carrusel />
  <Separador/>
  <Principal />
  <Formulario />
  <Footer />
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Principal from "./components/Principal.vue";
import Footer from "./components/Footer.vue";
import Carrusel from "./components/Carrusel.vue";
import Formulario from "./components/Formulario.vue";
import Separador from "./components/Separador.vue";
export default {
  components: {
    Navbar,
    Principal,
    Footer,
    Carrusel,
    Formulario,
    Separador
  }
};
</script>
