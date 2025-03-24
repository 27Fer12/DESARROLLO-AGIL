<template>
  
 <Nabvar />
 <Carrusel />
 <Principal />
 <CardPrincipal />
 <Footer />

</template>

<script>
import Nabvar from './components/Nabvar.vue';
import Carrusel from './components/Carrusel.vue';
import Principal from './components/Principal.vue';
import CardPrincipal from './components/CardPrincipal.vue';
import Footer from './components/Footer.vue';


export default {
  name: 'App',
  components: {
    Nabvar,
    Carrusel,
    Principal,
    CardPrincipal,
    Footer
  }
}

</script>