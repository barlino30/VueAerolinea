<template>
  <div class="FondoDest">
      Destinos
       <b-table striped hover :items="items"></b-table> 
  </div>
</template>

<script>
export default {
  name: 'Destinos',
  data() {
      return {
        items: [
         {lugar_entrada: 'Colombia', lugar_salida: 'España',Hora_salida: '22:00' },
         {lugar_entrada: 'Mexico',   lugar_salida: 'Italia', Hora_salida: '9:30'},
         {lugar_entrada: 'Alemania', lugar_salida: 'Rusia', Hora_salida: '13:00'},
         {lugar_entrada: 'Portugal', lugar_salida: 'Roma' , Hora_salida: '6:00'},
        ]
      }
    }

}
</script>

<style>
   .FondoDest{
      background-color: #F1F6F1; 
   }
</style>