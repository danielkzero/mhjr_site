<template>
  <div class="bg-white">
    <Cabecalho></Cabecalho>
    <SliderPrincipal></SliderPrincipal>
    <SliderSecundario></SliderSecundario>
    <ProdutosServicos></ProdutosServicos>
  </div>
  <MenuFlutuanteWhatsapp></MenuFlutuanteWhatsapp>
  <GoogleMaps></GoogleMaps>
  <Rodape></Rodape>
</template>

<script lang="ts">

import 'boxicons';
import SliderPrincipal from './components/SliderPrincipal.vue';
import SliderSecundario from './components/SliderSecundario.vue';
import ProdutosServicos from './components/ProdutosServicos.vue';
import MenuFlutuanteWhatsapp from './components/MenuFlutuanteWhatsapp.vue';
import GoogleMaps from './components/GoogleMaps.vue';
import Cabecalho from './components/Cabecalho.vue';
import Rodape from './components/Rodape.vue';
export default {
  components: {
    SliderPrincipal,
    SliderSecundario,
    ProdutosServicos,
    MenuFlutuanteWhatsapp,
    GoogleMaps,
    Cabecalho,
    Rodape
  },
  data() {
    return {
      navigation: [
        { name: 'Product', href: '#' },
        { name: 'Features', href: '#' },
        { name: 'Marketplace', href: '#' },
        { name: 'Company', href: '#' },
      ],
      mobileMenuOpen: false
    }
  }
}
</script>./components/SliderSecundario.vue