Como comentar no HTML?

Para realizar um comentário em HTML basta coloca o simbulo "<! --" e ao final do comentátio feche colocando "-->"

O que colocar dentro da tag HEAD?

No tag HEAD colocamos o titulos, links do site entre outras tags. Ela não é exibida no navegador# -NLW3
# -NLW3

Montagem da primeira tela<!DOCTYPE html>
<html lang="pt_BR">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Lar da meninas | Happy</title>

    <link
      rel="stylesheet"
      href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css"
      integrity="sha512-xodZBNTC5n17Xt2atTPuE1HxjVMSvLVW9ocqUKLsCC5CXdbqCmblAshOMAS6/keqq/sMZMZ19scR4PsZChSR7A=="
      crossorigin=""
    />

    <!-- Make sure you put this AFTER Leaflet's CSS -->
    <script
      src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js"
      integrity="sha512-XQoYMqMTK8LvdxXYG3nZ448hOEQiglfqkJs1NOQV44cWnUrBc8PkAOcXy20w0vlaXaVUearIOBhiXZ5V3ynxwA=="
      crossorigin=""
    ></script>

    <link rel="icon" href="./public/images/logo-icon.png" />

    <link rel="stylesheet" href="./public/css/main.css" />
    <link rel="stylesheet" href="./public/css/animation.css" />
    <link rel="stylesheet" href="./public/css/page-orphanage.css" />

    <link
      href="https://fonts.googleapis.com/css2? family = Nunito: wght @ 400; 600; 700; 800 & display = swap"
      rel="stylesheet"
    />
  </head>

  <body>
    <div id="page-orphanage">
      <aside class="animate-right sidebar" >

        <img src="./public/images/map-marker.svg" alt="Happy">

        <footer>
          <button onClick="history.back()">
            <img src="./public/images/arrow-back.svg" alt="Voltar">
          </button>
        </footer>


      </aside>

      <main class="animate-appear with-sidebar">
        <div class="orphanage-details">
          <img src="./public/images/home.jpg" alt="Lar das meninas" />

          <div class="images">
            <button onclick="selectImage(event)" class="active" type="button">
              <img src="./public/images/home.jpg" alt="Lar das meninas" />
            </button>

            <button onclick="selectImage(event)" type="button">
              <img src="./public/images/home.jpg" alt="Lar das meninas" />
            </button>

            <button onclick="selectImage(event)" type="button">
              <img src="./public/images/home.jpg" alt="Lar das meninas" />
            </button>

            <button onclick="selectImage(event)" type="button">
              <img src="./public/images/home.jpg" alt="Lar das meninas" />
            </button>

            <button onclick="selectImage(event)" type="button">
              <img src="./public/images/home.jpg" alt="Lar das meninas" />
            </button>

            <button onclick="selectImage(event)" type="button">
              <img src="./public/images/home.jpg" alt="Lar das meninas" />
            </button>
          </div>

          <div class="orphanage-details-content">
            <h1>Lar das meninas</h1>

            <p>
              Presta assistencia a crianças de 06 a 15 anos que se encontre em
              situação de risco e/ou vunerabilidade social.
            </p>

            <div class="map-container">
              <div id="mapid"></div>
              <footer>
                <a href="">Ver rotas no Google Maps</a>
              </footer>
            </div>

            <hr />

            <h2>Instruções para visitas</h2>

            <p>
              Venha como se sentir a vontade e traga muito amor e carinho para
              dar
            </p>

            <div class="open-details">
              <div class="hour">
                <img src="./public/images/clock.svg" alt="Horários" />
                Horário de visitas Das 18h até 8h
              </div>
              <div class="open-on-weekends">
                <img src="./public/images/info.svg" alt="Informações" />
                Atendemos fim de semana
              </div>
            </div>

            <button class="primary-button" type="button">
              <img
                src="./public/images/whatsapp.svg"
                alt="Chamar no whatsapp"
              />
              Entrar em contato
            </button>
          </div>
        </div>
      </main>
    </div>
    <script src="./public/scripts/page-orphanage.js"></script>
  </body>
</html>



