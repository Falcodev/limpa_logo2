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

<div class="container-float text-center phrase">

  <i>" A gente limpa você curte"</i><br />
  <span>Limpa Liogo.</span>
</div>


<div class="row text-center" style="height:300px;">
    <div class="col-md-8" style="background:#fcfcfe;">
        <p>Pecisa de um serviço de limpeza prático, qualificado e confiável? Chama a Limpa Logo. 👊 - Limpeza geral
          Você pode alugar toalhas, lençóis, travesseiros e muito mais. Tudo bem limpinho.
           Consulte os preços e itens disponíveis e levamos tudo até você em sacolas higienizadas com todo o cuidado e segurança.

- Limpeza pós-obra
- Serviço de check-in e check-out
- Aluguel de enxoval
- Lavagem de roupas.</p>
    </div>
  <div class="col-md-4 text-center back" >
  </div>
</div>


<h1>O que nos fazemos</h1>
<div class="container-float row text-center" style="min-height:400px;">
  <div class="col-md-6" style="background: #267E92;">
    <div class="row" style="min-height: 300px;margin-top:50px;">
      <div class="col-md-6" style="background: #267E92;">
        <span class="material-icons">local_laundry_service</span>
        <p  class="container" style="width:15em">
          Lavagem de roupas
        </p>
      </div>
      <div class="col-md-6" style="background: #267E92">
        <span class="material-icons">engineering</span>
        <p  class="container" style="width:15em">Limpeza pós obras</p>
      </div>
  </div>
  </div>
  <div class="col-md-6" style="background: #A8D5D2;">
    <div class="row" style="min-height: 300px;margin-top:50px;">

      <div class="col-md-6 " style="background: #A8D5D2;">
        <span class="material-icons">clean_hands</span>
        <br>
        <p  class="container" style="width:15em">
          Serviço de limpeza de apartamentos contando com uma equipe qualificada e disposta.
        </p>
      </div>

      <div class="col-md-6" style="background: #A8D5D2">
        <br>
        <span class="material-icons">checkroom</span>
        <br>
        <p  class="container" style="width:15em">
          Aluguel de enxoval de roupas a preços acessíveis.</p>
      </div>
  </div>
  </div>
</div>

<div class="container-float text-center row" style="background:popper;min-height:200px;padding-top:2%;padding-bottom:2%;">
  <div class="col-sm-3">
  </div>
  <div class="col-sm-2">
    <span class="material-icons">
location_on
</span>
    <!-- <img src="midias/imagens/map.png"> -->
    <h3>Endereço</h3>
    <p> Av. Oceano Indico, 255  Porto das Dunas, Aquiraz</p>
  </div>
  <div class="col-sm-2" style="border-left: solid grey 0.5px;border-right: solid grey 0.5px;">
    <span class="material-icons">call</span>
    <h3>Telefone</h3>

    <a href="https://api.whatsapp.com/send?1=pt_BR&amp;phone=5585999912017" target="_blank">
        		(85) 9 9991-2017</a>
  </div>
  <div class="col-sm-2">
    <span class="material-icons">alternate_email</span>
    <h3>Email</h3>
    <p>contato@limpalogo.com.br</p>
  </div>
  <div class="col-sm-3">
  </div>
</div>
<div class="container-float" style="min-height:50px;background:grey;">
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

<style scoped>
/* Make the image fully responsive */
.carousel-inner img{
    width: 100%;
    height: 100%;
}
.back{
/* background-image: url("midias/imagens/football.png")  no-repeat center center scroll; */
position: relative;
display: table;
width: 100%;
height: 100%;
-webkit-background-size: cover;
-moz-background-size: cover;
-o-background-size: cover;
background-size:cover;

}

.phrase{
    padding-top: 2.5%;
    background: white;
    min-height:200px;
}
p{
  padding: 0%;
}

h2{
  font-family:Arial;
}

</style>
