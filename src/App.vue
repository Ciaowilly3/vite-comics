<script>
import Header from "./components/Header.vue";
import ComicsItem from "./components/ComicsItem.vue";
import Merch from "./components/MerchComponent.vue";
import Footer from "./components/Footer.vue";
export default {
  components: { Header, ComicsItem, Merch, Footer },
};
</script>

<template>
  <Header></Header>
  <div class="fluid-container"></div>
  <ComicsItem></ComicsItem>
  <Merch></Merch><Footer></Footer>
</template>

<style scoped lang="scss">
.fluid-container {
  height: 400px;
  background-image: url(../src/assets/jumbotron.jpg);
  background-size: cover;
}
</style>
