<template>
  <div class="FondoAero">
      Aerolineas
      <b-table striped hover :items="items"></b-table>
  </div>
</template>

<script>
export default {
  name: 'Aerolineas',
  data() {
      return {
        items: [
         {Clase: 'VIP', compañia: 'Avianca',Capacidad: '368 personas' },
         {Clase: 'Economica',   compañia: 'SisePuede', Capacidad: '230 personas'},
         {Clase: 'Ejecutiva', compañia: 'Continental Airlines',Capacidad: '100 personas'},
         {Clase: 'VIP', compañia: 'airtran' , Capacidad: '600 personas'},
        ]
      }
    }
}
</script>

<style>
   .FondoAero{
      background-color: #F1F6F1; 
   }
</style>