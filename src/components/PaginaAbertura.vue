<script>
export default {
  data() {
    return {
      imagem: [new URL("./img/modelo.jpg", import.meta.url).href],
    };
  },
};
</script>

<template>
  <header id="header" class="header">
    <div class="texto-botao">
      <h1 class="texto-header">Faça seu teste agora</h1>
      <button class="botao-header">Começar</button>
    </div>
    <div class="img-header">
      <img :src="imagem[0]" alt="" />
    </div>
  </header>
</template>

<style>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.texto-header {
  font-size: 5em;
}
.botao-header {
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
.botao-header:hover {
  background-color: #ffffff;
  color: rgb(0, 0, 0);
}
.img-header {
  display: block;
  box-shadow: 0 8px 20px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}
</style>
