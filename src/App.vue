
<template>

  <Header />
  <Navbar />
  <Carrusel />
  <Card />
   <Footer />
</template>
<script>

import Navbar from "./components/Navbar.vue";
import Header from "./components/Header.vue";
import Principal from "./components/Principal.vue";
import Footer from "./components/Footer.vue";
import Carrusel from "./components/Carrusel.vue";
import Card from "./components/Card.vue";
export default {
  components: {
    Navbar,
    Principal,
    Footer,
    Carrusel,
    Header,
    Card
  }
};

</script>
