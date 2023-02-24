<template>
    <div class="Fondo">
        <div class="SobreN">
            <center>
            <h1><font size="20" color="#d2691e">Aerolinea si se puede</font></h1>
            <br>
            <h2><font size="6" color="#5E78EB">Nuestra empresa es especialista a dejar varados a nuestros clientes en zonas armadas, 
                pero no se preocupe dejaremos un testamento en su nombre y nos quedaremos con su dinero
                asegurando una pequeña parte a su familia.</font>
            </h2>
            </center>
        </div>
        <div class="ImagenA">
            <b-img src="https://i.pinimg.com/736x/4c/8f/5d/4c8f5dc0c4722e233d012f0f00dc9154.jpg" height="300px"></b-img>
        </div>
    </div>
</template>

<script>
export default {
  name: 'NavBar'

}
</script>

<style>
    .Fondo{
    margin-left: 0%;
    margin-right: 0%;
    height: 6%;
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size:cover;
    overflow: hidden;

    background-image: url("https://www.ef.com.co/blog/wp-content/uploads/sites/25/2018/02/viajala.png");
    
  }

  .SobreN{
      float: left;
      width: 500px;
      height: 250px;
      margin-top: 10%;
      margin-left: 10%;
      margin-bottom: 20%;
  }
  .ImagenA{
      float: right;
      margin-top: 10%;
      margin-right: 16%;
  }
</style>