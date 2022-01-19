<template>
  <div id="app">
    <Header />
    <MainServices />
    <MainProducts />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import MainServices from "./components/MainServices.vue";
import MainProducts from "./components/MainProducts.vue";

export default {
  name: "App",
  components: {
    Header,
    MainServices,
    MainProducts,
  },
};
</script>

<style lang="scss" scoped>
@import './styles/general.scss';

</style>
