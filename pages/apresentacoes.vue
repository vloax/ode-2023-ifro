<template>
  <header>
    <div class="home-scope">
      <div class="image-icons">
        <img src="/initialPageIcon.png" alt="">
      </div>
      <p class="home-text">HOME</p>
    </div>


    <div class="image-logo-search">
      <img src="/logoif.png" alt="">
    </div>

    <div class="search-scope">
      <div class="image-icons">
        <img src="/icons8-pesquisar-48.png" alt="">
      </div>
      <input v-model="text" class="input-model">
    </div>
  </header>

  <nav class="navbar-principal">
    <NuxtLink to="/" class="n-link-base">
      QUEM SOMOS?
    </NuxtLink>
    <NuxtLink to="/" class="n-link-base">
      APRESENTAÇÕES EM EVENTOS
    </NuxtLink>
    <NuxtLink to="/" class="n-link-base">
      PUBLICAÇÕES
    </NuxtLink>
    <NuxtLink to="/" class="n-link-base">
      CONTATO
    </NuxtLink>
  </nav>

  <main class="presentation-principal-form">
    <div class="presentation-form">
      <h1 class="presentation-title">GERAÇÕES SOCIAIS E EXPECTATIVAS DE FUTURO NO BRASIL DURANTE A PANDEMIA: ANÁLISE DE
        DADOS DO DATAFOLHA COM LINGUAGEM R</h1>
      <div class="horizontal-line"></div>
      <div class="presentation-info-about">
        <h4 class="main-presentation-autors">Por: Vitor Melo</h4>
        <h4 class="place-presentation">XIII CONNEPI - 2022</h4>
      </div>
      <p class="presentation-text-first">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut et massa mi. Aliquam in hendrerit urna. Pellentesque
        sit amet sapien fringilla, mattis ligula consectetur, ultrices mauris. Maecenas vitae mattis tellus. Nullam quis
        imperdiet augue. Vestibulum auctor ornare leo, non suscipit magna interdum eu. Curabitur pellentesque nibh nibh,
        at maximus ante fermentum sit amet. Pellentesque commodo lacus at sodales sodales. Quisque sagittis orci ut diam
        condimentum, vel euismod erat placerat. In iaculis arcu eros, eget tempus orci facilisis id.Lorem ipsum dolor sit
        amet, consectetur adipiscing elit. Ut et massa mi. Aliquam in hendrerit urna. Pellentesque sit amet sapien
        fringilla, mattis ligula consectetur, ultrices mauris.
      </p>

      <div class="graphic-img">
        <img class="img-graph" src="/graphicImage.png" alt="">
      </div>

      <p class="presentation-text-first">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut et massa mi. Aliquam in hendrerit urna. Pellentesque
        sit amet sapien fringilla, mattis ligula consectetur, ultrices mauris. Maecenas vitae mattis tellus. Nullam quis
        imperdiet augue. Vestibulum auctor ornare leo, non suscipit magna interdum eu. Curabitur pellentesque nibh nibh,
        at maximus ante fermentum sit amet. Pellentesque commodo lacus at sodales sodales. Quisque sagittis orci ut diam
        condimentum, vel euismod erat placerat. In iaculis arcu eros, eget tempus orci facilisis id.Lorem ipsum dolor sit
        amet, consectetur adipiscing elit. Ut et massa mi. Aliquam in hendrerit urna. Pellentesque sit amet sapien
        fringilla, mattis ligula consectetur, ultrices mauris.
      </p>


    </div>

    <div class="other-presentations">
      <h2 class="card-title">OUTROS:</h2>

      <div class="other-presentations-all-cards">
        <div class="other-presentations-card">
          <div class="other-presentations-main-img">
            <img src="/edutecMainImg.png" alt="">
          </div>
          <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>


        <div class="other-presentations-card">
          <div class="other-presentations-main-img">
            <img src="/edutecMainImg.png" alt="">
          </div>
          <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>

        <div class="other-presentations-card">
          <div class="other-presentations-main-img">
            <img src="/edutecMainImg.png" alt="">
          </div>
          <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>

        <div class="other-presentations-card">
          <div class="other-presentations-main-img">
            <img src="/edutecMainImg.png" alt="">
          </div>
          <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>
        
        <div class="other-presentations-card">
          <div class="other-presentations-main-img">
            <img src="/edutecMainImg.png" alt="">
          </div>
          <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>

        <div class="other-presentations-card">
          <div class="other-presentations-main-img">
            <img src="/edutecMainImg.png" alt="">
          </div>
          <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>
      </div>
    </div>
  </main>

  <div class="horizontal-line"></div>

  <footer>
    <div class="footer-content">
      <div class="footer-img">
        <img src="/logoBlackIfro.png" alt="">
      </div>

      <div class="navigation-items">
        <NuxtLink to="/" class="n-link-base">
          QUEM SOMOS?
        </NuxtLink>
        <NuxtLink to="/" class="n-link-base">
         APRESENTAÇÕES EM EVENTOS
        </NuxtLink>
        <NuxtLink to="/" class="n-link-base">
         PUBLICAÇÕES
        </NuxtLink>
        <NuxtLink to="/" class="n-link-base">
         CONTATO
        </NuxtLink>
      </div>

    
      <p class="direito">Todos os direitos reservados. © 2023 IFRO</p>

    </div>
  </footer>
</template>

<script setup>

</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@800&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap');

body {
  font-family: 'Inter', Sans-Serif;
  margin: 0 auto;
}

main {
  margin: 70px 250px 40px 250px;
}

.home-text {
  font-size: 1.3rem;
}

header {
  background-color: #118D3B;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px;
}

.input-model {
  margin-left: 15px;
  background: #FFFFFF;
  border: 1px #000000;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 10px;
  padding: 3px;
}

.image-logo-search {
  width: 100px;
  display: flex;
  align-items: center;
}

.image-logo {
  display: flex;
  align-items: center;
}

.home-text {
  padding-left: 15px;
  color: white;
}

.home-scope,
.search-scope {
  display: flex;
  align-items: center;
}

.navbar-principal a {
  text-decoration: none;
  color: white;
}

.navbar-principal {
  display: flex;
  gap: 30px;
  justify-content: center;
  padding: 10px 0px 10px 0px;
  background-color: #16C551;
}

.presentation-title {
  font-size: 1.4rem;
  text-align: justify;
}

.main-presentation-autors,
.place-presentation {
  font-family: 'Roboto', sans-serif;
  font-size: 1.0rem;
  margin: 2px 0px 30px 0px;
}

.presentation-form {
  display: block;
  text-align: center;
}

.presentation-text-first {
  text-align: justify;
}


.horizontal-line {
  border: 1px solid #000000;
  margin-bottom: 0px;
}

.presentation-info-about {
  display: flex;
  margin-top: 0px;
  padding: 0px;
  justify-content: space-between;
}

.img-graph {
  width: 100%;
}

.other-presentations-all-cards {
  display: flex;
  flex-wrap: wrap;
  text-align: start;
  gap: 45px;
  margin: 0 auto;
}

.card-title {
  font-size: 1.6rem;
  margin: 40px 0px 60px 0px; 
}

.other-presentations-main-img {
  background: #D9D9D9;
  box-shadow: inset 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 10px;
  padding: 35px;
  margin: 0 auto;
}

.other-presentations-card {
  width: 250px;
  height: 250px;

}

.footer-content {
  font-family: 'Roboto', sans-serif;
  text-decoration: none;
  display: flex;
  justify-content: space-between;
  text-align: center;
  align-items: center;
  padding: 20px;
}

.navigation-items a {
  text-decoration: none;
  color: black;
  padding: 10px;
}

.direito {
  font-size: 0.8rem;
  display: flex;
  justify-content: flex-end;
}

</style>