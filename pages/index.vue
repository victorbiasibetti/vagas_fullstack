<template>
  <div class="container">
    <div class="header">
      <div class="logo">
        <img src="../layout/assets/group-12.png" class="logo-img" />
        <div class="labels">
          <img src="../layout/assets/user.png" />
          <div>
            <span> Entrar </span>
            <span> | </span>
            <span> Criar conta </span>
          </div>
        </div>
      </div>
    </div>

    <div class="app">
      <div class="titulo">
        <h1 class="a-4">Título da página</h1>
        <p class="a-6">
          Informação curta e direta sobre o app divulgado na página com foco nas
          funcionalidades
        </p>
        <div class="icons">
          <img src="../layout/assets/google-play_3.png" />
          <img
            class="apple"
            src="../layout/assets/download-on-the-app-store-badge-ptbr-rgb-blk-092917_3.png"
          />
        </div>
      </div>
      <div class="mobile">
        <img src="../layout/assets/group-9.png" />
      </div>
    </div>

    <div class="information">
      <div>
        <img src="../layout/assets/group-33.png" />
        <h2>Título</h2>
        <p>
          Texto corrido com informações que vão ser preenchidas depois que a
          página estiver pronta.
        </p>
      </div>

      <div>
        <img src="../layout/assets/alarm-clock-2.png" />
        <h2>Título</h2>
        <p>
          Texto corrido com informações que vão ser preenchidas depois que a
          página estiver pronta.
        </p>
      </div>

      <div>
        <img src="../layout/assets/ic-notifications-none.png" />
        <h2>Título</h2>
        <p>
          Texto corrido com informações que vão ser preenchidas depois que a
          página estiver pronta.
        </p>
      </div>
    </div>

    <div class="video">
      <div class="video-titulo">
        <h1>Vídeo promocional do app</h1>
        <p>
          O vídeo mostra todas as funcionalidades e você vai conferir como
          funciona e ver como é fácil e simples de usar o app, falando do uso e
          seus benefícios
        </p>
      </div>

      <img src="../layout/assets/youtube-image.png" />
    </div>

    <div class="marcas">
      <h1>Marcas do app em destaque</h1>
      <div class="texto">
        <div>
          <h3>
            Título
          </h3>
          <p>
            Marcação de texto para ser preenchido depois da página ficar pronta,
            enquanto isso segue com o texto marcando a página
          </p>
        </div>
        <div>
          <h3>
            Título
          </h3>
          <p>
            Marcação de texto para ser preenchido depois da página ficar pronta,
            enquanto isso segue com o texto marcando a página
          </p>
        </div>
        <div>
          <h3>
            Título
          </h3>
          <p>
            Marcação de texto para ser preenchido depois da página ficar pronta,
            enquanto isso segue com o texto marcando a página
          </p>
        </div>
      </div>

      <div class="logos">
        <div><img src="../layout/assets/logo-placeholder-2-x.png" /></div>
        <div><img src="../layout/assets/logo-placeholder-2-x.png" /></div>
        <div><img src="../layout/assets/logo-placeholder-2-x.png" /></div>
        <div><img src="../layout/assets/logo-placeholder-2-x.png" /></div>
        <div><img src="../layout/assets/logo-placeholder-2-x.png" /></div>
        <div><img src="../layout/assets/logo-placeholder-2-x.png" /></div>
        <div><img src="../layout/assets/logo-placeholder-2-x.png" /></div>
        <div><img src="../layout/assets/logo-placeholder-2-x.png" /></div>
        <div><img src="../layout/assets/logo-placeholder-2-x.png" /></div>
        <div><img src="../layout/assets/logo-placeholder-2-x.png" /></div>
        <div><img src="../layout/assets/logo-placeholder-2-x.png" /></div>
        <div><img src="../layout/assets/logo-placeholder-2-x.png" /></div>
        <div><img src="../layout/assets/logo-placeholder-2-x.png" /></div>
        <div><img src="../layout/assets/logo-placeholder-2-x.png" /></div>
        <div><img src="../layout/assets/logo-placeholder-2-x.png" /></div>
        <div><img src="../layout/assets/logo-placeholder-2-x.png" /></div>
      </div>
    </div>
  </div>
</template>

<script></script>

<style>
@import '../layout/colors.css';
img {
  max-width: 100%;
}

.logo {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  max-width: 100%;
  max-height: 20%;
  padding: 20px 0;
  flex-wrap: wrap;
}

.labels {
  padding: 0 5%;
  display: flex;
  align-items: center;
}

.labels img {
  margin-right: 15px;
}

.labels div {
  align-items: center;
  width: fit-content;
}

.logo-img {
  padding: 0 5%;
}

.app {
  display: flex;
  flex-wrap: wrap;
  align-items: center;

  margin: 0 auto;
  padding: 20px 5%;
}

.mobile > img {
  width: 60%;
  margin: 0 20%;
}

.titulo {
  align-items: center;
  max-height: 150px;
}

.titulo > h1 {
  padding-bottom: 20px;
}

.titulo > p {
  font-size: 14px;
  padding-bottom: 40px;
  padding-right: 60px;
}
.apple {
  margin-left: 100px;
}

.information {
  background: #f7ffdc;
  padding: 40px;
  display: flex;

  flex-wrap: wrap;
  margin: 0 auto;
  align-items: center;
}
.information > div {
  flex: 1 1 300px;

  background: #ffffff;
  border-radius: 5px;
  margin: 10px;
  padding: 70px;
}

.information > div > img {
  margin: 0 40%;
  justify-items: center;
  margin-bottom: 20px;
}

.information > div > h2 {
  margin: 0 40%;
  margin-bottom: 20px;
  justify-items: center;
}
.information > div > p {
  justify-items: center;
  align-items: center;
  margin: 10px;
  text-align: center;
}

.video {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding-top: 100px;
  padding-bottom: 50px;
}

.video-titulo {
  width: 50%;
}

.video-titulo > h1 {
  padding-bottom: 20px;
  text-align: center;
}

.video-titulo > p {
  text-align: center;
  padding-bottom: 20px;
}

.video > img {
  width: 50%;
}

.marcas {
  display: flex;
  flex-wrap: wrap;
  padding-bottom: 100px;
}

.marcas > h1 {
  width: 100%;
  text-align: center;
  margin-bottom: 30px;
}

.marcas > .texto {
  display: flex;
  flex-direction: column;
  align-content: space-around;
  padding: 0 5%;
  max-width: 50%;
  height: 120%;
  margin-top: 30px;
}
.marcas > .texto > div {
  display: flex;
  flex-direction: column;
  align-items: flex-start;

  padding-right: 30%;
  padding-bottom: 10%;
}
.marcas > .texto > div > h3 {
  padding-bottom: 20px;
}

.marcas > .logos {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  max-width: 50%;
  grid-gap: 10px 20px;
  margin-top: 30px;
}

.marcas > .logos > div {
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 5px;
  padding: 5% 20% 5% 20%;
  box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.19);
}

.logos > div:nth-child(1) {
  background: #4a90e2;
}
.logos > div:nth-child(6) {
  background: #ff4600;
}
.logos > div:nth-child(11) {
  background: #9746d5;
}
.logos > div:nth-child(16) {
  background: #fedb00;
}
</style>
