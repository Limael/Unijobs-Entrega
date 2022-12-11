<template>
  <div class="columns is-flex is-flex-direction-column" id="app">

    <div class="column ">
      <nav class="navbar is-align-items-center is-light is-flex" role="navigation" aria-label="main navigation">
        <div class="navbar-brand">
          <router-link to="/landing" class="navbar-item"> <img src="./assets/imagens/Logo-uni.png" alt="Logo" /> </router-link>

        </div>


        <div class="campo-pesquisa">
          <form class='search-bar'>
            <input placeholder="Pesquisar" />
            <button type='submit'><img src='./assets/imagens/Union.png' /></button>
          </form>
        </div>



        <div class="navbar-end">
          <div class='navbar-item'>
            <router-link to="/about" class="navbar-item">Entrar</router-link>
          </div>
        </div>


      </nav>
    </div>
    <router-view />
  </div>
</template>

