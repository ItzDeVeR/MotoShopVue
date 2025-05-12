<script>
import Header from "./components/Header.vue"
import MainDiv from "./components/MainDiv.vue"
import TopSales from "./components/TopSales.vue"
import OurBrands from "./components/OurBrands.vue"
import VideoMoto from "./components/VideoMoto.vue"
import FooterTop from "./components/FooterTop.vue"
import FooterBottom from "./components/FooterBottom.vue"

export default {
  data() {

  },
  components: {
    Header,
    MainDiv,
    TopSales,
    OurBrands,
    VideoMoto,
    FooterTop,
    FooterBottom
  },
  methods: {

  }
}
</script>

<template>
  <Header />
  <MainDiv />
  <TopSales />
  <OurBrands />
  <VideoMoto />
  <FooterTop />
  <FooterBottom />
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Comfortaa&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  background-color: #000;
  color: #fff;
  font-family: "Comfortaa", sans-serif;
}
</style>