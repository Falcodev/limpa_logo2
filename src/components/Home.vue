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
      <img  src="./a2.png" alt="Chicago"  >
    </div>
    <div class="carousel-item">
      <img  src="./b.png" alt="Chicago">
    </div>
    <div class="carousel-item">
      <img  src="./c2.png" alt="Chicago">
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

<h1 >O que nos fazemos</h1>


<div class="container-float row text-center">
  <div class="col-md-4">
  <img  src="./Limpa_logo.png" alt="Limpa Logo" height="270px" >
  </div>
    <div class="col-md-7">
        <p>
        Pecisa de um serviço de limpeza prático, qualificado e confiável? Chama a Limpa Logo. 👊
        Atuamos no Porto das Dunas e no cumbuco. Nossa especialidade é limpeza de apartamntos de veraneio.
        Vinhemos para simplificar a sua vida, com limpeza rápida e sobre demanda, podemos economizar
        tempo e dinheiro.Com pacotes mensais, conseguimos atender apartamentos destinados a locação de temporada,
        hoteis e famílias com alta demanda.

        </p>
    </div>
  <div class="col-md-4 text-center" >
  </div>
</div>


<div class=" row text-center">
<h2>Serviço</h2>
<div class="col-md-6 direito" id="a"></div>
<div class="col-md-6 esquerdo" id="a"></div>

      </div>
<div class=" row text-center">
  <div class="col-md-6 direito" >

    <div class="row">
      <div class="col-md-6">
        <span class="material-icons md-60 esquerdo">clean_hands</span>
        <h5>Limpeza de Apartamentos </h5>
        <p  class="container">
          Contamos com uma grande equipe qualificada,ágil e disposta.
        </p>
      </div>
      <div class="col-md-6">
        <span class="material-icons md-60 esquerdo">engineering</span>
        <h5>Limpeza pós obras </h5>
        <p  class="container">
        Uma limpeza mais intensa, com materias apropriados para a situação.
        </p>
      </div>
  </div>
  </div>
  <div class="col-md-6 esquerdo">
    <div class="row">
      <div class="col-md-6 ">
        <span class="material-icons md-60 direito">local_laundry_service</span>
      <h5>Lavagem de Roupas </h5>
        <p  class="container">
          Tercerizamos, e fazemos a gestão do enxoval de roupas,
          para simplificar a limpeza do dia a dia.

        </p>
      </div>

      <div class="col-md-6">
        <span class="material-icons md-60 direito">checkroom</span>
        <h5>Aluguel de enxoval</h5>
        <p  class="container">
          Disponibilizamos essa opção para solucionar pontualmente a alta demanda do enxoval.</p>
      </div>
  </div>
  </div>
</div>

<div class="container-float text-center row" id="footer1" >
  <div class="col-sm-3"></div>
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
  <div class="col-sm-3"></div>
</div>
<div class="footer">
  <a href="https://www.falcodev.com.br/#/">Falco desenvolvimento de websites.</a>
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
a {
  color: #e6e6e6;
  text-decoration: none;
  cursor: pointer;
}
a:hover {
  color: #eee;
  text-decoration: none;
  cursor: pointer;
}
p{
  margin-top: auto;
  margin-bottom: auto;
}
.row{
  width: 100%;
  padding-top: 0px;
  padding-bottom: 0px;
  margin-right: auto;
  margin-left: auto;
  align-items: center;
}
.carousel-inner {
    max-width: 100%;
    }
.carousel-inner img{
    object-fit:cover;
    max-width: 100%;
    height: 600px;
}
.citacao{
    padding-top: 2.5%;
    background: white;
    min-height:200px;
}
.col-md-6.esquerdo{
  background: #A8D5D2;
}
.col-md-6.direito{
  background: #206975;
}
.material-icons.md-60 {
   font-size: 60px;
}
.material-icons.md-48 {
   font-size: 48px;
}
.material-icons.direito {
   color: #206975;
 }
 .material-icons.esquerdo{
   color: #a8d5d2;
 }
 .limpa_logo_logo{
   float: right;
   max-height: 250px;
   max-width: 100px;
 }
 .footer{
   text-align: center;
   background-color: #1a1a1a;
   color: #ddd;
 }
 h2{
   width: 100%;
   position: absolute;
   margin-top: 0px;
   z-index: 1;
 }
 #a{
   height: 30px;
   }

</style>
