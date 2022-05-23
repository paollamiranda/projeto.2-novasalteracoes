<script>
export default {
  data() {
    return {
      logo: new URL("./img/logo.1.png", import.meta.url).href,
      imagem: new URL("./img/modelo.ini-2.png", import.meta.url).href,
    };
  },
};
</script>

<template>
  <main id="main" class="main">
    <div class="texto-botao">
      <h1 class="texto-main">Faça seu teste agora</h1>
      <button class="botao-main">Começar</button>
    </div>
    <div class="img-main">
      <img :src="imagem" alt="" />
    </div>
  </main>
</template>

<style>
.main {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.texto-main {
  font-size: 5em;
}
.img-main {
  width: 330px;
  height: 340px;
  padding-top: 100px;
  padding-right: 350px;
}
.botao-main {
  display: flex;
  background-color: black;
  color: white;
  font-weight: bold;
  font-size: 2.5em;
  border-radius: 60px;
  padding: 20px;
  box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  -webkit-transition-duration: 0.4s;
  transition-duration: 0.4s;
}
.botao-main:hover {
  background-color: #ffffff;
  color: rgb(0, 0, 0);
}
</style>
