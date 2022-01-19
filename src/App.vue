<template>
  <div id="app">
    <Header />
    <MainServices />
    <MainProducts />
    <MainReviewsandPosts />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import MainServices from "./components/MainServices.vue";
import MainProducts from "./components/MainProducts.vue";
import MainReviewsandPosts from "./components/MainReviewsandPosts.vue";

export default {
  name: "App",
  components: {
    Header,
    MainServices,
    MainProducts,
    MainReviewsandPosts,
  },
};
</script>

<style lang="scss" scoped>
@import './styles/general.scss';

</style>
