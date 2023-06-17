<template>
  <div>
    <div id="title_carousel">
      <h3>Event Galleries</h3>
    </div>
    <div class="carousel-container">
    <div class="swiper-container" ref="swiperContainer">
      <div class="swiper-wrapper">
        <!-- Aquí van las diapositivas del carrusel -->
        <div
          class="swiper-slide"
          v-for="(numero, index) in numeros"
          :key="index"
        >
          <Card :ruta="`https://picsum.photos/id/${getRandomNumber()}/900/590`" />
        </div>
        <!-- Agrega más diapositivas según tus necesidades -->
      </div>
      <div class="swiper-pagination"></div>
      <div class="swiper-button-next"></div>
      <div class="swiper-button-prev"></div>
    </div>
  </div>
</div>

</template>

<script>
import Swiper from "swiper/bundle";
import "swiper/swiper-bundle.css";
import Card from "./Card.vue";

export default {
  mounted() {
    const swiper = new Swiper(this.$refs.swiperContainer, {
      slidesPerView: "auto",
      spaceBetween: 10,
      navigation: {
        nextEl: ".swiper-button-next",
        prevEl: ".swiper-button-prev",
      },
      pagination: {
        el: ".swiper-pagination",
      },
    });

    swiper.init();
  },
  components: {
    Card,
  },
  data() {
    return {
      numeros: [1, 2, 3, 4, 5, 6],
    };
  },
  methods: {
    getRandomNumber() {
      return Math.floor(Math.random() * (0+300));
    },
  },
};
</script>
