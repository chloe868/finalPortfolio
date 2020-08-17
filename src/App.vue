<template>
  <div class="background">
      <Header></Header>
      <AppBody></AppBody>
      <Footer></Footer>
  </div>
</template>
<style>
.background {
  background-image: linear-gradient(to top, #000000c5 20%, #ffffff 107%);
  height: 100vh;
}
@media screen and (max-width: 700px) {
  .background {
    height: 100vh;
  }
}
</style>
<script>
import Header from "components/frame/Header.vue";
import AppBody from "components/frame/Body.vue";
import Footer from "components/frame/Footer.vue";
export default {
  name: "app",
  components: {
    Header,
    Footer,
    AppBody
  }
};
</script>