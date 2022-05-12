<script>
export default {
   data() {
    return {
      logo: new URL("./img/logo.jpeg", import.meta.url).href,
      };
  },
};
</script>
<template>
  <header class="logo">
   <div class="header-img-logo">
     <img :src="logo" alt="">
   </div>
 </header>

  <Article class="bloco-pergunta">
    <div class="pergunta">Pergunta!!!</div>
    <div class="botoes-perguntas">
      
    </div>
  </Article>
</template>

<style>
.bloco-pergunta {
  width: 700px;
  /* height: 300px; */
  border: 1px solid rgb(0, 0, 0);
  border-radius: 15px;
  padding: 60px;
  margin: 50px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.bloco-pergunta .pergunta {
  background-color: #c4c4c4;
  border-radius: 50px;
  width: 60%;
  padding: 15px;
  font-weight: bolder;
  text-align: center;
  font-size: 1.9em;
}
.bloco-pergunta .botoes-perguntas {
  background-color: #c4c4c4;
  border-radius: 10px;
  width: 100%;
  padding: 60px;
  margin: 40px 0;

}

.bloco-pergunta .botoes-perguntas {
  display: flex;
  background-color: #c4c4c4;
  border-radius: 20px;
  padding-top: 10px;
  padding-bottom: 8px;
  padding-left: 20px;
  width: 60%;
}
.botoes-perguntas button {
  background-color: black;
  color: white;
  font-weight: bold;
  font-size: 1.5em;
  border-radius: 10px;
}
</style>
