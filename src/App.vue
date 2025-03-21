<template>
  <Navbar />
  <Carrusel />
  <Principal />
  <Footer />
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Principal from "./components/Principal.vue";
import Footer from "./components/Footer.vue";
import Carrusel from "./components/Carrusel.vue";
export default {
  components: {
    Navbar,
    Principal,
    Footer,
    Carrusel
  }
};
</script>
