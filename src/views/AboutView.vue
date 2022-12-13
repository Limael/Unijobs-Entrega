<template>
  <div class="columns is-flex is-flex-direction-column is-align-items-center about">
    <div class="mt-6 column is-flex is-flex-direction-column is-align-items-center">
      <figure class="image is-128x128">
        <img class="is-rounded" src="../assets/imagens/perfil.png">
      </figure>
      <h1 class="title">Lucas Lucas</h1>
      <h2 class="subtitle">Engenharia de Software</h2>
    </div>


    <div class="column is-three-quarters">
      <div class="box">
        <div class="column is-flex is-justify-content-space-around">

          <div class="controle">
            <input class="input input is-medium is-rounded" type="text" placeholder="@lucasinsta">

          </div>
          <div class="controle">
            <input class="input is-medium is-rounded" type="text" placeholder="(45) 99819-3666">
          </div>

        </div>

        <div class="column is-flex is-justify-content-space-around">

          <div class="controle">
            <input class="input is-medium is-rounded" type="text" placeholder="lucasFacebook">
            <span class="icon is-small is-left">
              <i class="crack"></i>
            </span>


          </div>
          <div class="controle">
            <input class="input is-medium is-rounded" type="text" placeholder="lucas@lucas.com">
          </div>

        </div>

      </div>
    </div>

    <div class="column">
      <button class="button is-rounded is-success">Criar anúncio</button>
    </div>

    <div class="card is-flex is-flex-direction-column is-align-items-center">
      <div class="blue-triangle-top"></div>
      <img class="card-icon mt-5" src="../assets/imagens/livro.png" alt="Logo" />
      <div class="card-titulo">
        <h4>Dou aulas de inglês</h4>
      </div>
      <div class="title-line"></div>
      <div class="card-content pt-1">
        <div class="content has-text-centered is-flex is-align-items-center">
          Lorem ipsum leo risus, porta ac consectetur ac, vestibulum at eros. Donec id elit non mi porta gravida at
          eget metus. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Cras
          mattis consectetur purus sit amet fermentum.
        </div>
        <div class="user-card-information is-flex is-align-items-center">
          <figure class="image is-64x64">
            <img class="is-rounded" src="../assets/imagens/perfil.png" alt="Logo" />
          </figure>
          <div class="user-card-name ml-2 is-flex is-flex-direction-column is-align-items-flex-start">
            <h1> Otavio Augusto</h1>
            <small>Engenharia de Software</small>
          </div>
        </div>

      </div>
      <div class="green-triangle-bottom"></div>
    </div>

  </div>
</template>
