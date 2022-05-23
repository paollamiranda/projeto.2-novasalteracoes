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
</template>
<style>
.header.logo {
  display: flex;
  justify-content: center;
  align-items: center;
}
.header-img-logo img {
  width: 200px;
  height: 80px;
  align-items: center;
  padding: 40px 0 5px 0;
  margin-left: 500px;
}
</style>
