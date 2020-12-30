<template>
<div>
  <nav class="navbar is-danger" id="navbar">
    <div class="nabvar-brand" id="navbar">
        <img src="buscolo1.png" alt="Bulma: Free, open source, and modern CSS framework based on Flexbox" width="200" height="130">
    </div>
  </nav>
  <div class="container">
    <div class="columns">
      <div class="column" id="margin">
        <div class="columns is-mobile">
          <div class="column">
            <h1 id="title" class="title is-1">Encuentra</h1>
          </div>
        </div>
        <div class="columns is-mobile">
          <div class="column is-offset-1">
            <h2 class="title is-3">Servicios</h2>
          </div>
        </div>
        <div class="columns is-mobile">
          <div class="column is-offset-2">
            <h2 class="title is-3">Profesionales</h2>
          </div>
        </div>
        <div class="columns is-mobile" id="googleplaycolumn">
          <div class="column">
            <figure>
              <img src="GOOGLEPLAY.png" width="200" height="130" alt="">
            </figure>
          </div>
          <div class="column">
            <figure>
              <img src="Appstore.png" width="200" height="130" alt="">
            </figure>
          </div>
        </div>
      </div>
      <div class="column is-offset-3" >
          <img id="mimage" src="ss_uenrii.png" alt="">
      </div>
    </div>
    <div class="columns is-centered">
      <div class="column is-4">
        <figure>
          <img src="media1.png">
        </figure>
        <p class="is-size-5">
          Buscar servicios profesionales nunca ha sido tan fácil. Tenga acceso a una base de datos de profesionales en su zona, desde su celular. Plomeros, electricistas, técnicos y mucho mas!
        </p>
      </div>
      <div class="column is-7">
        <figure>
          <img src="atjobs.png" alt="">
        </figure>
      </div>
    </div>
    <div class="columns">
      <div class="column is-6">
            <h1 id="title" class="title is-1 has-text-centered">Nosotros</h1>
      </div>
      <div class="column is-6">
      </div>
    </div>
    <div class="columns">
      <div class="column is-6">
        <figure>
          <img src="logo2.jpg" alt="">
        </figure>
      </div>
      <div class="column is-7">
        <p class="is-size-5">
          Somos una aplicación hecha en Nicaragua para ayudar a los profesionales a 
          tener una mayor exposición en la red. 
          No les pasa que algunas veces necesitan de servicio profesional urgente? 
        </p>
      </div>
    </div>
    <div class="columns">
      <div class="column is-5">
          <p class="is-size-5">
            <span class="is-size-3">
            Siempre 
            </span>
          hay que preguntar a conocidos por referencias: si conocen a algún 
          veterinario que puede llegar a la casa cuánto antes; o algún buen técnico para 
          reparar el aire acondicionado; entre muchas otras situaciones  que pueden 
          surgir repentinamente.

          </p>
      </div>
      <div class="column is-6">
        <figure>
          <img src="training.jpg">
        </figure>
      </div>
    </div>
    <div class="columns ">
      <div class="column is-6">
        <figure>
          <img src="buscolo.png" alt="">
        </figure>
      </div>
      <div class="column is-6">
        <div class="columns">
          <div class="column">
            <p class="is-size-5">
              Por esta razon creamos la plataforma de Busco App, para que los  
              profesionales en distintas áreas puedan ofrecer su servicios 
              y estar más conectados con los usuarios que puedan requerir de ellos. 
            </p>
          </div>
        </div>
        <div class="columns">
          <p class="is-size-3">
            <span class="is-size-2">
              ¿Que estás esperando?
            </span>
            Para buscar y ofrecer Sevicios profesionales
          </p>
        </div>
        <div class="columns is-mobile">
          <div class="column">
            <figure>
              <img src="GOOGLEPLAY.png" width="200" height="130" alt="">
            </figure>
          </div>
          <div class="column">
            <figure>
              <img src="Appstore.png" width="200" height="130" alt="">
            </figure>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div id="footer">
    <div class="container">
      <div class="columns is-gaples">
        <div class="column is-2">
        </div>
      </div>
      <div class="columns is-gapless">
        <div class="column is-2">
          <div class="columns is-gapless">
            <div class="column is-12">
              <a href="Terminosycondiciones" id="textfooter">
                <span id="textfooter">
                  Terminos y Condiciones
                </span>
              </a>
            </div>
          </div>
          <div class="columns is-gapless">
            <div class="column is-12">
              <a id="textfooter">
                <span id="textfooter">
                  Politica de Privacidad
                </span>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {}
</script>

<style>
#navbar{
  width:  100% !important;
  padding-top: 5px !important;
}
#mimage{
  width: 430px ;
  height: 600px;
}
#margin{
  margin-top: 110px;
}
#title{
  font-size: 60px !important;
}
#googleplaycolumn{
  margin-top: 20px;
}
#tryes{
  display: inline;
}
#footer{
  height: 200px;
  background-color: #f14668;
  width: 100%;
}
#textfooter{
  color: white;
  font-weight: 700;
}

</style>
