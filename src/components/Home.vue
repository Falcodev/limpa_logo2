<template>
  <div class="hello">
    <div id="demo" class="carousel slide" data-ride="carousel">
  <!-- Indicators -->
  <ul class="carousel-indicators">
    <li data-target="#demo" data-slide-to="0" class="active"></li>
    <li data-target="#demo" data-slide-to="1"></li>
    <li data-target="#demo" data-slide-to="2"></li>
  </ul>

  <!-- The slideshow -->
  <div class="carousel-inner container-float">
    <div class="carousel-item active">
      <img  src="./1800600.png" alt="Chicago" >
    </div>
    <div class="carousel-item">
      <img  src="./1800600_2.png" alt="Chicago" >
    </div>
    <div class="carousel-item">
      <img  src="./1800600_3.png" alt="Chicago" >
    </div>
  </div>

  <!-- Left and right controls -->
  <a class="carousel-control-prev" href="#demo" data-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </a>
  <a class="carousel-control-next" href="#demo" data-slide="next">
    <span class="carousel-control-next-icon"></span>
  </a>
</div>

<div class="container-float text-center citacao">
  <i>" A gente limpa você curte "</i><br />
  <span>Limpa Logo.</span>
</div>


<h1>O que nos fazemos</h1>
<div class="row text-center" style="height:300px;">
    <div class="col-md-8" style="background:#fcfcfe;">
        <p>
        Pecisa de um serviço de limpeza prático, qualificado e confiável? Chama a Limpa Logo. 👊
        Atuamos no Porto das Dunas e no cumbuco. Nossa especialidade é limpeza de apartamntos de veraneio.
        Vinhemos para simplificar a sua vida, com limpeza rápida e sobre demanda, podemos economizar
        tempo e dinheiro.Com pacotes mensais, conseguimos atender apartamntos destinados a locação de temporada,
        hoteis e famílias com alta demanda.

        </p>
    </div>
  <div class="col-md-4 text-center" >
  </div>
</div>

<h1>Serviços</h1>
<div class="container-float row text-center">
  <div class="col-md-6 direito" >
    <div class="row">
      <div class="col-md-6">
        <span class="material-icons md-60 esquerdo">clean_hands</span>
        <p  class="container">
          Serviço de limpeza de apartamentos contando com uma equipe qualificada e disposta.
        </p>
      </div>
      <div class="col-md-6">
        <span class="material-icons md-60 esquerdo">engineering</span>
        <p  class="container">Limpeza pós obras</p>
      </div>
  </div>
  </div>
  <div class="col-md-6 esquerdo">
    <div class="row">
      <div class="col-md-6 ">
        <span class="material-icons md-60 direito">local_laundry_service</span>
        <br>
        <p  class="container">
          Lavagem de roupas
        </p>
      </div>

      <div class="col-md-6">
        <span class="material-icons md-60 direito">checkroom</span>
        <p  class="container">
          Aluguel de enxoval de roupas a preços acessíveis.</p>
      </div>
  </div>
  </div>
</div>

<div class="container-float text-center row" >
  <div class="col-sm-3">
  </div>

  <div class="col-sm-2">
    <span class="material-icons md-48 direito">location_on</span>
    <h3>Endereço</h3>
    <p> Av. Oceano Índico, 255  Porto das Dunas, Aquiraz</p>
  </div>

  <div class="col-sm-2">
    <span class="material-icons md-48 direito">call</span>
    <h3>Telefone</h3>
    <a href="https://api.whatsapp.com/send?1=pt_BR&amp;phone=5585999912017">(85) 9 9991-2017</a>
  </div>
  <div class="col-sm-2">
    <span class="material-icons md-48 direito">alternate_email</span>
    <h3>Email</h3>
    <p>contato@limpalogo.com.br</p>
  </div>
  <div class="col-sm-3">
  </div>
</div>

</div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
    }
  }
}
</script>

<style>
.row{
  width: 100%;
  margin-top: 30px;
  margin-bottom: 30px;
}
.carousel-inner img{
    width: 100%;
    height: 100%;
}
.citacao{
    padding-top: 2.5%;
    background: white;
    min-height:200px;
}

a{
  color: black;
  text-decoration: none;
}
.col-md-6.esquerdo{
  background: #A8D5D2;
}
.col-md-6.direito{
  background: #267E92;
}
.material-icons.md-60 {
   font-size: 60px;
}
.material-icons.md-48 {
   font-size: 48px;
}
.material-icons.direito {
   color: #267E92;
 }
 .material-icons.esquerdo{
   color: #a8d5d2;

 }


</style>
