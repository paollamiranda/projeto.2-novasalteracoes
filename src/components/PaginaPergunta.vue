<script>
export default {
  data() {
    return {
      logo: new URL("./img/logo.1.png", import.meta.url).href,
    };
  },
};
</script>
<template>
  <header class="logo">
    <div class="header-img-logo">
      <img :src="logo" alt="" />
    </div>
  </header>

  <Article class="bloco-pergunta">
    <div class="pergunta">Pergunta</div>
    <button class="botoes-perguntas"> sla qualquer pergunta</button>

  </Article>
</template>

<style>
.bloco-pergunta {
  width: 700px;
  /* height: 300px; */
  border: 1px solid rgb(0, 0, 0);
  border-radius: 15px;
  padding-right: 30px;
  margin: 40px;
  margin-left: 250px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.bloco-pergunta .pergunta {
  border: 1px solid rgb(0, 0, 0);
  border-radius: 400px;
  margin-top: 15px;
  margin-left: px;
  width: 60%;
  padding: 10px;
  font-weight: bolder;
  text-align: center;
  font-size: 2em;
}

.bloco-pergunta .botoes-perguntas {
  border: 1px solid rgb(0, 0, 0);
  border-radius: 10px;
  width: 100%;
  padding: 60px;
  margin: 40px 0;
}

.bloco-pergunta .botoes-perguntas {
  display: flex;
  border: 1px solid rgb(0, 0, 0);
  border-radius: 20px;
  padding-top: 10px;
  padding-bottom: 8px;
  padding-left: 20px;
  width: 80%;
}
.botoes-perguntas button {
  background-color: black;
  color: white;
  font-weight: bold;
  font-size: 1.5em;
  border-radius: 10px;
}
</style>
