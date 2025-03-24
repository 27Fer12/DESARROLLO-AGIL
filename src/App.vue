<template>
  <Navbar />
  <Cuerpo />
  <Separador/>
  <Card />
  <Separador2 />
  <Principal />
  <Separador3 />
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
import Cuerpo from "./components/Cuerpo.vue";
import Card from "./components/Card.vue";
import Separador2 from "./components/separador2.vue";
import Separador3 from "./components/Separador3.vue";
export default {
  components: {
    Navbar,
    Principal,
    Footer,
    Carrusel,
    Formulario,
    Separador,
    Cuerpo,
    Card,
    Separador2,
    Separador3
  }
};
</script>
