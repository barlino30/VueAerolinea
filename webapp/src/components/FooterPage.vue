<template>
  <div class="FondoFoot">
    <div class="Facebook">
      <a href="https://www.facebook.com/"><b-img src="https://i.pinimg.com/originals/ce/c8/a6/cec8a6239de29acbfcfee0ccec995b9f.png" height="50px"></b-img></a>
    </div>

    <div class="Instagram">
      <a href="https://www.instagram.com/?hl=es"><b-img src="http://assets.stickpng.com/images/580b57fcd9996e24bc43c521.png" height="50px"></b-img></a>
    </div>

    <div class="Twitter">
      <a href="https://twitter.com/"><b-img src="http://assets.stickpng.com/images/580b57fcd9996e24bc43c53e.png" height="50px"></b-img></a>
    </div>

    <div class="Contactos">
      <center>
      <h1><font size="4" color="white">Contactos</font></h1>
      
      <h1><font size="3" color="white">Telefono: +57 8689465 celular: 3182831938 <br>
      Direccion: Cra 51G #22-35h Fax:941 446 227</font></h1>
      </center>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FooterPage'
}
</script>

<style>
   .FondoFoot{
      background-color: #2e2f30; 
      background-size:cover;
      overflow: hidden;
   }
   .Facebook{
      float: left;
      margin-left: 3%;
      margin-right: 0.5;
      margin-bottom: 6%;
      margin-top: 2%;
    }
    .Instagram{
      float: left;
      margin-left: 3%;
      margin-right: 0.5;
      margin-bottom: 6%;
      margin-top: 2%;
    }
    .Twitter{
      float: left;
      margin-left: 3%;
      margin-right: 0.5;
      margin-bottom: 6%;
      margin-top: 2%;
    }

    .Contactos{
      float: right;
      width: 400px;
      height: 100px;
      margin-left: 2%;
      margin-right: 6%;
      margin-bottom: 6%;
      margin-top: 2%;
    }
</style>