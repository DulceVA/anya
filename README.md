<!DOCTYPE html>
<html>
  <head>
    <title>W3.CSS Template</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <style>
    body, h1,h2,h3,h4,h5,h6 {font-family: "Montserrat", sans-serif}
    .w3-row-padding img {margin-bottom: 12px}
    /* Set the width of the sidebar to 120px */
    .w3-sidebar {width: 120px;background: #222;}
    /* Add a left margin to the "page content" that matches the width of the sidebar (120px) */
    #main {margin-left: 120px}
    /* Remove margins from "page content" on small screens */
    @media only screen and (max-width: 600px) {#main {margin-left: 0}}
    </style>
  </head>
<body class="w3-black">


<!-- Icon Bar (Sidebar - hidden on small screens) -->
<nav class="w3-sidebar w3-bar-block w3-small w3-hide-small w3-center">
  <!-- Avatar image in top left corner -->
  <img src="https://media.vogue.mx/photos/614182f08a46e41e935b4b33/4:3/w_2206,h_1655,c_limit/anya-taylor-joy-actriz-de-gambito-de-dama.jpg" style="width:100%">
  <a href="#" class="w3-bar-item w3-button w3-padding-large w3-black">
    <i class="fa fa-home w3-xxlarge"></i>
    <p>INICIO</p>
  </a>
  <a href="#about" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-user w3-xxlarge"></i>
    <p>SOBRE MI</p>
  </a>
  <a href="#photos" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-eye w3-xxlarge"></i>
    <p>FOTOS</p>
  </a>
  <a href="#contact" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-envelope w3-xxlarge"></i>
    <p>CONTACTO</p>
  </a>
</nav>


<!-- Navbar on small screens (Hidden on medium and large screens) -->
<div class="w3-top w3-hide-large w3-hide-medium" id="myNavbar">
  <div class="w3-bar w3-black w3-opacity w3-hover-opacity-off w3-center w3-small">
    <a href="#" class="w3-bar-item w3-button" style="width:25% !important">HOME</a>
    <a href="#about" class="w3-bar-item w3-button" style="width:25% !important">ABOUT</a>
    <a href="#photos" class="w3-bar-item w3-button" style="width:25% !important">PHOTOS</a>
    <a href="#contact" class="w3-bar-item w3-button" style="width:25% !important">CONTACT</a>
  </div>
</div>


<!-- Page Content -->
<div class="w3-padding-large" id="main">
  <!-- Header/Home -->
  <header class="w3-container w3-padding-32 w3-center w3-black" id="home">
    <h1 class="w3-jumbo"><span class="w3-hide-small">Soy</span> Anya Taylor Joy.</h1>
    <p>Actriz y modelo.</p>
    <img src="https://media.vogue.mx/photos/614182f08a46e41e935b4b33/4:3/w_2206,h_1655,c_limit/anya-taylor-joy-actriz-de-gambito-de-dama.jpg" alt="boy" class="w3-image" width="992" height="1108">
  </header>


  <!-- About Section -->
  <div class="w3-content w3-justify w3-text-grey w3-padding-64" id="about">
    <h2 class="w3-text-light-grey">Anya Taylor Joy</h2>
    <hr style="width:200px" class="w3-opacity">
    <p>se dio a conocer por su interpretación en "La bruja" de A24, que cosechó sus excelentes críticas en su estreno en 2015, en el Festival de Cine de Sundance.
      En su primer largometraje, el guionista y director Robert Eggers cuenta la historia de una familia de peregrinos asediada por una fuerza sobrenatural.
      Después ganó el Premio al Actor Revelación en los Premios Gotham y el Premio a la Mejor Revelación Femenina en The Empires por su actuación.
    </p>
    <h3 class="w3-padding-16 w3-text-light-grey">Mis habilidades</h3>
    <p class="w3-wide">Actuación</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:95%"></div>
    </div>
    <p class="w3-wide">Modelaje</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:85%"></div>
    </div>
    <p class="w3-wide">Doblaje</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:80%"></div>
    </div><br>
   
    <div class="w3-row w3-center w3-padding-16 w3-section w3-light-grey">
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">30+</span><br>
        Peliculas/Series
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">1+</span><br>
        Globo de oro
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">20+</span><br>
        Nominaciones
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">28+</span><br>
        Pasarelas
      </div>
    </div>


    <button class="w3-button w3-light-grey w3-padding-large w3-section">
      <i class="fa fa-download"></i> Descargar el resumen
    </button>
   
    <!-- Grid for pricing tables -->
    <h3 class="w3-padding-16 w3-text-light-grey">Mis precios</h3>
    <div class="w3-row-padding" style="margin:0 -16px">
      <div class="w3-half w3-margin-bottom">
        <ul class="w3-ul w3-white w3-center w3-opacity w3-hover-opacity-off">
          <li class="w3-dark-grey w3-xlarge w3-padding-32">Basico</li>
          <li class="w3-padding-16">Historia</li>
          <li class="w3-padding-16">Mención</li>
          <li class="w3-padding-16">Prenda</li>
          <li class="w3-padding-16">Saludo</li>
          <li class="w3-padding-16">
            <h2>$ 320</h2>
            <span class="w3-opacity">Kit</span>
          </li>
          <li class="w3-light-grey w3-padding-24">
            <button class="w3-button w3-white w3-padding-large w3-hover-black">Comprar</button>
          </li>
        </ul>
      </div>


      <div class="w3-half">
        <ul class="w3-ul w3-white w3-center w3-opacity w3-hover-opacity-off">
          <li class="w3-dark-grey w3-xlarge w3-padding-32">Pro</li>
          <li class="w3-padding-16">Visita</li>
          <li class="w3-padding-16">Fotos</li>
          <li class="w3-padding-16">Video</li>
          <li class="w3-padding-16">Clase</li>
          <li class="w3-padding-16">
            <h2>$ 599</h2>
            <span class="w3-opacity">Kit</span>
          </li>
          <li class="w3-light-grey w3-padding-24">
            <button class="w3-button w3-white w3-padding-large w3-hover-black">Comprar</button>
          </li>
        </ul>
      </div>
    <!-- End Grid/Pricing tables -->
    </div>
   
    <!-- Testimonials -->
    <h3 class="w3-padding-24 w3-text-light-grey">Mis actuaciones</h3>  
 <img src="https://www.nacionflix.com/__export/1668276701297/sites/debate/img/2022/11/12/anya-taylor-joy-disney-the-witch.jpg_423682103.jpg" alt="Avatar" class="w3-left w3-circle w3-margin-right" style="width:80px">    <p><span class="w3-large w3-margin-right">La bruja.</span> Actuación.</p>
    <p>Obra del cine de terror.</p><br>
   
    <img src="https://vader.news/__export/1607715732830/sites/gadgets/img/2020/12/11/006-queens-gambit-vogue-051120-courtesy-netflix.jpg_1220958698.jpg" alt="Avatar" class="w3-left w3-circle w3-margin-right" style="width:80px">
    <p><span class="w3-large w3-margin-right">Gambito de dama.</span> Hit de Netflix.</p>
    <p>Basada en hechos reales.</p>
  <!-- End About Section -->
  </div>
 
  <!-- Portfolio Section -->
  <div class="w3-padding-64 w3-content" id="photos">
    <h2 class="w3-text-light-grey">Mis fotos</h2>
    <hr style="width:200px" class="w3-opacity">


    <!-- Grid for photos -->
    <div class="w3-row-padding" style="margin:0 -16px">
      <div class="w3-half">
        <img src="https://cinefilosoficial.com/wp-content/uploads/2021/05/anya-talylor-portada.jpg" style="width:100%">
        <img src="https://hips.hearstapps.com/hmg-prod/images/anya-taylor-joy-premios-oscar-2024-alfombra-roja-vestido-junon-dior-1949-elle-65ee4f1b35a43.jpg?crop=1.00xw:0.670xh;0,0.0383xh&resize=1200:*" style="width:100%">
        <img src="https://media.vogue.mx/photos/614182f28a46e41e935b4b36/master/pass/anya-taylor-joy-portada-de-vogue-mexico.jpg" style="width:100%">
      </div>


      <div class="w3-half">
        <img src="https://scontent-lax3-2.xx.fbcdn.net/v/t39.30808-6/274215271_489829919177357_293402570072384021_n.jpg?_nc_cat=107&ccb=1-7&_nc_sid=5f2048&_nc_ohc=nce58FnpYgsQ7kNvgF598l_&_nc_ht=scontent-lax3-2.xx&oh=00_AfDSE4IxcFpAFjC2b5F-0BPf7nKYAVuDH9QZMg7PE1j5Lg&oe=663AF75E" style="width:100%">
        <img src="https://editorialtelevisa.brightspotcdn.com/dims4/default/8002112/2147483647/strip/true/crop/1200x676+0+12/resize/1000x563!/quality/90/?url=https%3A%2F%2Fk2-prod-editorial-televisa.s3.us-east-1.amazonaws.com%2Fbrightspot%2F91%2F0a%2F494690734413a74a6c7645a3f849%2Fanya-taylor-joy-en-desfile-de-dior.jpeg" style="width:100%">
        <img src="https://hips.hearstapps.com/hmg-prod/images/anya-taylor-joy-attends-the-los-angeles-premiere-of-focus-news-photo-1605525756.?resize=2048:*" style="width:100%">
        <img src="https://cdn-3.expansion.mx/dims4/default/9e1b2b4/2147483647/strip/true/crop/1200x800+0+0/resize/1200x800!/format/webp/quality/60/?url=https%3A%2F%2Fcdn-3.expansion.mx%2F63%2F59%2F69644585428e82b02d3737e25d44%2Fgettyimages-1392268582.jpg" style="width:100%">
      </div>
    <!-- End photo grid -->
    </div>
  <!-- End Portfolio Section -->
  </div>


  <!-- Contact Section -->
  <div class="w3-padding-64 w3-content w3-text-grey" id="contact">
    <h2 class="w3-text-light-grey">Contactame</h2>
    <hr style="width:200px" class="w3-opacity">


    <div class="w3-section">
      <p><i class="fa fa-map-marker fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Buenos Aires, AR</p>
      <p><i class="fa fa-phone fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Teléfono: +00 151515</p>
      <p><i class="fa fa-envelope fa-fw w3-text-white w3-xxlarge w3-margin-right"> </i> Email: anyataylor@mail.com</p>
    </div><br>
    <p>Envia preguntas:</p>


    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Nombre" required name="Name"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Email" required name="Email"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Tema" required name="Subject"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Mensaje" required name="Message"></p>
      <p>
        <button class="w3-button w3-light-grey w3-padding-large" type="submit">
          <i class="fa fa-paper-plane"></i> ENVIAR MENSAJE
        </button>
      </p>
    </form>
  <!-- End Contact Section -->
  </div>
 
<!-- Footer. This section contains an ad for W3Schools Spaces. You can leave it to support us. -->
<footer class="w3-content w3-padding-64 w3-text-grey w3-xlarge">
  <i class="fa fa-facebook-official w3-hover-opacity"></i>
  <i class="fa fa-instagram w3-hover-opacity"></i>
  <i class="fa fa-snapchat w3-hover-opacity"></i>
  <i class="fa fa-pinterest-p w3-hover-opacity"></i>
  <i class="fa fa-twitter w3-hover-opacity"></i>
  <i class="fa fa-linkedin w3-hover-opacity"></i>
 <p class="w3-small">Conoce más de mi día día!</p>
 <a class="w3-button w3-round-xxlarge w3-small w3-light-grey" href="https://www.w3schools.com/spaces" target="_blank">Empieza ya</a>
 <!-- End footer -->
</footer>


<!-- END PAGE CONTENT -->
</div>


</body>
</html>



