<template>
  <div class="FondoNe">
      
      <b-form inline>
        <div class="Cajita">
        <b-form-input
        id="inline-form-input-name"
        class="mb-2 mr-sm-2 mb-sm-0"
        placeholder="Nombre Completo"
        ></b-form-input>
        </div>

        <div class="CajitaC">
        <b-input-group prepend="@" class="mb-2 mr-sm-2 mb-sm-0">
        <b-form-input id="inline-form-input-username" placeholder="Email"></b-form-input>
        </b-input-group>
        </div>

        <div class="CajitaI">
        <b-button variant="primary">Save</b-button>
        </div>
    </b-form>
  </div>
</template>

<script>
export default {
  name: 'FormN'
}
</script>

<style>
   .FondoNe{
        background: #212529;
        background-size:cover;
        overflow: hidden;
    }
  .Cajita{
      float: left;
      width: 300px;
      height: 20px;
      margin-left: 6%;
      margin-right: 2%;
      margin-bottom: 3%;
      margin-top: 2%;
    }

  .CajitaI{
      float: right;
      width: 20px;
      height: 20px;
      margin-left: 0%;
      margin-right: 20%;
      margin-bottom: 0%;
      margin-top: 2%;
    }

  .CajitaC{
      float: left;
      width: 300px;
      height: 20px;
      margin-left: 6%;
      margin-right: 10%;
      margin-bottom: 0%;
      margin-top: 2%;
    } 
</style>