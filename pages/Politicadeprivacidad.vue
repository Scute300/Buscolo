<template>
    <div>
        <nav class="navbar is-danger" id="navbar">
            <div class="nabvar-brand" id="navbar">
                <a href="/">
                    <img src="buscolo1.png" alt="Bulma: Free, open source, and modern CSS framework based on Flexbox" width="200" height="130">
                </a>
            </div>
        </nav>
        <div class="container">

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
                    <a id="textfooter">
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
    export default {
        
    }
</script>

<style scoped>
#navbar{
  width:  100% !important;;
  padding-top: 5px !important;
}
#footer{
  height: 200px;
  background-color: #f14668;
  width: 100%;
  margin-top: 2800;
}
#textfooter{
  color: white;
  font-weight: 700;
}

</style>