
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
      <input class="input-model">
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
</template>

<style>
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
  font-weight: 500;
  justify-content: center;
  padding: 10px 0px 10px 0px;
  background-color: #16C551;
}

</style>