<script>
import PaginaAbertura from "@/components/PaginaAbertura.vue";
import PaginaPergunta from "@/components/PaginaPergunta.vue";
import PaginaIntroducao from "./components/PaginaIntroducao.vue";
import HeaderCabecalho from "./components/HeaderCabecalho.vue";

// import PrincipalContent from "./components/PrincipalContent.vue";

export default {
  components: { PaginaAbertura, PaginaPergunta, PaginaIntroducao, HeaderCabecalho },
};
</script>
<template>
  <!-- <PaginaAbertura /> -->
  <PaginaPergunta />
   <!-- <PaginaIntroducao /> -->
   <!-- <HeaderCabecalho /> -->
</template>
<style></style>
