<template>
  <div>
     <NavBar/>
     <SobreNosotros/>
     <FormN/>
     <Destinos/>
     <Aerolineas/>
     <FooterPage/>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import SobreNosotros from './components/SobreNosotros.vue'
import FormN from './components/FormN.vue'
import Destinos from './components/Destinos.vue'
import Aerolineas from './components/Aerolineas.vue'
import FooterPage from './components/FooterPage.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    SobreNosotros,
    FormN,
    Destinos,
    Aerolineas,
    FooterPage
  }
}
</script>

<style>
  
</style>
