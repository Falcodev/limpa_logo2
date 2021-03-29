<template>
<div>
<div class="hero">
  <i>A gente limpa você curte.</i><br />
</div>


<div class="container-float row text-center">
  <div class="col-md-4">
  <img  src="./Limpa_logo.png" alt="Limpa Logo" height="270px" >
  </div>
    <div class="col-md-7">
      <h1 >O que nos fazemos</h1>
      <br>
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

<div class="servicos">
  <h1>Serviços</h1>
</div>


<div class=" row text-center">
  <div class="col-md-6 direito" >

    <div class="row">
      <div class="col-md-6">
        <span class="material-icons md-60 esquerdo">clean_hands</span>
        <h5>Limpeza de Apartamentos </h5>
        <p  class="container">
          Contamos com uma grande equipe qualificada, ágil e disposta.
        </p>
      </div>
      <div class="col-md-6">
        <span class="material-icons md-60 esquerdo">engineering</span>
        <h5>Limpeza pós obras </h5>
        <p  class="container">
        Uma limpeza mais intensa, com materias apropriados para cada situação.
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
<!-- <div class="row instagram">
<div class="col-sm-4">
<h1>Já conferiu nosso instagram ?</h1>
</div>
<div class="col-sm-8 text-center">
  <img src="./12.png" alt="Instagram" id="instagram">
<h6>@limaplogo</h6>
</div>


</div> -->

<div class="container-float  row" id="footer1" >
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
  <a href="https://www.instagram.com/limpalogo/" id="insta"><img  src="./insta.png" alt="Limpa Logo" height="20px"></a>
  <a id='falco' href="https://www.falcodev.com.br/#/">Falco desenvolvimento de websites.</a>
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
  font-family: times;
  color: #292929;
  text-decoration: none;
  cursor: pointer;
}
a:hover {
  color: #ddd;
  text-decoration: none;
  cursor: pointer;
}
p{
  font-family:times;
  color: #292929;
  margin-top: 10px;
  margin-bottom: 15px;
}
.hero{
  background-image:url('c3.png');
  background-size: cover;
  background-position: center;
  height: 500px;
  color: white;
  font-size: 50px;
  font-weight: bold;
  font-family: monospace;
  overflow:hidden;
  position: static;
  display: flex;
  justify-content: center;
  align-items: center;
}

.row{
  position: relative;
  background-color: none;
  width: 100%;
  padding-top: 30px;
  padding-bottom: 0px;
  margin: auto;
}
.servicos{
  text-align: center;
}
.citacao{
    padding-top: 2.5%;
    background: white;
    min-height:200px;
}
.col-md-6.esquerdo{
  background-color: #A8D5D2;
}
.col-md-6.direito{
  background-color: #206975;
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
   display: inline-block;
   text-align: center;
   width: 100%;
   padding-top: 20px;
   padding-bottom: 20px;
   background-color: #292929;
   color: #ddd;
 }
 .footer img{

 margin-left: auto;
 margin-right:auto;
 }

 h1{
   text-align: center;
 }
 i{
text-align: center;
 }
 .container-float .text-center .row{

 }
 .col-sm-2{
   width: auto;
   height: 100%;
  }
#falco{
  display: none;
  position: absolute;
  border-bottom: 0px;
  border-right: 0px;
  margin-right: 0px;
  padding-right: 0px;
  text-align:right;
  color:#ddd;
}
 #insta{
   position: relative;
   text-align: center;
   }
  #footer1{
    position: relative;
    /* align-items: baseline; */
    text-align: center;
    background-image:url('11-3.png');
    background-size: cover;
    background-position: center;
  }


</style>
