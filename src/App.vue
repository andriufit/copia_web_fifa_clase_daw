<script setup>
  import mainNewComponent from './components/mainNewComponent.vue';
  import featuredNewsComponent from './components/featuredNewsComponent.vue';
  import homeCarrouselComponent from './components/homeCarrouselComponent.vue';

</script>

<template>
  <header>
    <div class="mini-container">
      <ul>
        <li>
          <a href="#">Compra entradas</a>
        </li>
        <li>
          <a href="#">Fifa+</a>
        </li>
        <li>
          <a href="#">Fifa store</a>
        </li>
        <li>
          <a href="#">Inside fifa</a>
        </li>
      </ul>
    </div>
    <div class="header-container">
      <a href="/" >
        <img src="/img/logo.webp">
      </a>
      <nav>
        <ul>
          <li>
            <a href="#">
              Torneos
            </a>
          </li>
          <li>
            <a href="#">
              Central de partidos
            </a>
          </li>
          <li>
            <a href="#">
              Noticias
            </a>
          </li>
          <li>
            <a href="#">
              Ranking
            </a>
          </li>
          <li>
            <a href="#">
              Ver en FIFA+
            </a>
          </li>
          <li>
            <a href="#">
              Jugar
            </a>
          </li>
          <li>
            <a href="#">
              Tienda
            </a>
          </li>
          <li>
            <a href="#">
              Inside FIFA
            </a>
          </li>
        </ul>
      </nav>
      <div class="header-icons-container">
        <ul>
          <li>
            <a href="#">
              <font-awesome-icon icon="magnifying-glass" />
            </a>
          </li>
          <li>
            <a href="#">
              <font-awesome-icon icon="globe" />
            </a>
          </li> 
          <li>
            <a href="#">
              <font-awesome-icon icon="user" />
            </a>
          </li>
        </ul>
      </div>
    </div>
  </header>

  <main>
    <!--
      newTitle: String,
        newImg: String,
        newText: String,
        newSubtitle: String,
        newLink: String,
        //Img banner izquierda
        bannerImg: String,
        bannerTitle: String,
        bannerText: String,
        bannerLink: String
    -->
    <mainNewComponent 
      newTitle="RPD de Corea domina a Japón y se consagra en Bogotá"
      newImg="https://digitalhub.fifa.com/transform/c15dcef4-786e-41da-9d02-47551e5cb3a6/Korea-DPR-v-Japan-Final-FIFA-U-20-Women-s-World-Cup-Colombia-2024?focuspoint=0.53,0.51&io=transform:fill,height:868,width:1536&quality=75"
      newText="Le ganó 1 a 0 al equipo de Kano, con gol de Choe Il Son, y consiguió su tercer título en la categoría."
      newSubtitle="Copa Mundial Femenina Sub 20 de la FIFA 2024"
      newLink="/"
      bannerImg="https://digitalhub.fifa.com/transform/e46fd151-6204-4597-ab3b-0b1fc2431194/FIFA_Futsal-WC-2024_Promo-Box-Asset_Desktop_992x1536"
      bannerTitle="Copa Mundial de Futsal de la FIFA Uzbekistán 2024"
      bannerText="Encuentra noticias, streamings en directo, resúmenes y los resultados en Uzbekistán"
      bannerLink="/"
      />

    <featuredNewsComponent/>

    <homeCarrouselComponent title="Titulo de prueba" href="/"/>

  </main>

  <footer>

  <div class="first-footer-container">
    <div class="footer-logo">
      <a href="/" >
        <img src="/img/logo.webp">
      </a>
    </div>
    <div class="social-container">
      <ul>
        <li><a href="#"><font-awesome-icon icon="fa-brands fa-x-twitter" /></a></li>
        <li><a href="#"><font-awesome-icon icon="fa-brands fa-facebook-f" /></a></li>
        <li><a href="#"><font-awesome-icon icon="fa-brands fa-instagram" /></a></li>
        <li><a href="#"><font-awesome-icon icon="fa-brands fa-youtube" /></a></li>
        <li><a href="#"><font-awesome-icon icon="fa-brands fa-tiktok" /></a></li>
      </ul>
    </div>
    <div class="footer-text">
      <p>
        Descárgate ya la FIFA App para disfrutar de más contenidos
      </p>
    </div>
    <div class="app-container">
      <a href="#">
        <img src="/img/play.png">
      </a>
      <a href="#">
        <img src="/img/ios.png">
      </a>  
    </div>
  </div>

  <div class="icons-footer-container">

    <div class="partners-container">
      <h5>FIFA PARTNERS</h5>
      <div class="partners-list">
        <div class="partners-list-items">
          <img src="https://digitalhub.fifa.com/m/1f95073924b11b7f/webimage-fifa_fp_aramco_dbgr.png">
        </div>
        <div class="partners-list-items">
          <img src="https://digitalhub.fifa.com/m/2af08fef5011c616/webimage-fifa_fp_adidas-co_dbgr.png">
        </div>
        <div class="partners-list-items">
          <img src="https://digitalhub.fifa.com/m/6db992f31d19388d/webimage-fifa_fp_cocacola-co_dbgr.png">
        </div>
        <div class="partners-list-items">
          <img src="https://digitalhub.fifa.com/m/61d5210539dcf25e/webimage-fifa_fp_hyundai-kia_dbgr.png">
        </div>
        <div class="partners-list-items">
          <img src="https://digitalhub.fifa.com/m/39eacec45668b079/webimage-fifa_fp_qatar-airways_co_dbgr.png">
        </div>
        <div class="partners-list-items">
          <img src="https://digitalhub.fifa.com/m/681a0ca7f3290bb1/webimage-fifa_fp_visa_dbgr.png">
        </div>
      </div>
    </div> 
      
    <div class="sponsors-container">
      <h5>SPONSORS</h5>
      <div class="sponsors-list">
        <div class="sponsors-list-items">
          <img src="https://digitalhub.fifa.com/m/1b8d7de6b9df12/webimage-fifa_sp_abi_dbgr.png">
        </div>
        <div class="sponsors-list-items">
          <img src="https://digitalhub.fifa.com/m/32b98794efb0aed2/webimage-fifa_sp_bank-america_dbgr.png">
        </div>
        <div class="sponsors-list-items">
          <img src="https://digitalhub.fifa.com/m/4f361a12607a0d16/webimage-fifa_sp_lays_dbgr.png">
        </div>
        <div class="sponsors-list-items">
          <img src="https://digitalhub.fifa.com/m/6c22c901d1a6e10e/webimage-fifa_sp_mcdonalds_dbgr.png">
        </div>
        <div class="sponsors-list-items">
          <img src="https://digitalhub.fifa.com/m/177eb15b0cae9c7a/webimage-fifa_sp_mengniu_dbgr.png">
        </div>
        <div class="sponsors-list-items">
          <img src="https://digitalhub.fifa.com/m/7ddc8410de09f15c/webimage-fifa_sp_unilever-dove_dbgr.png">
        </div>
        <div class="sponsors-list-items">
          <img src="https://digitalhub.fifa.com/m/1eef9c7fe5e61474/webimage-fifa_sp_verizon_dbgr.png">
        </div>
      </div>
    </div>

  </div>

  </footer>
</template>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined');
  @import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
  @import "./../src/assets/styles.scss";
</style>
