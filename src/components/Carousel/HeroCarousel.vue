<template>
  <div class="carousel">
    <div class="carousel-inner">
      <carousel-item
        v-for="(slide, index) in slides"
        :slide="slide"
        :key="index"
        :current-slide="currentSlide"
        :index="index"
        :direction="direction"
      ></carousel-item>
      <carousel-controls @prev="prev" @next="next"></carousel-controls>
    </div>
  </div>
</template>

<script>
import CarouselItem from "./CarouselItem.vue";
import CarouselControls from "./CarouselControls.vue";

export default {
  components: {
    CarouselItem,
    CarouselControls,
  },
  data() {
    return {
      slides: [
        {
          id: 1,
          image: "https://picsum.photos/id/1032/1200/600",
        },
        {
          id: 1,
          image: "https://picsum.photos/id/1033/1200/600",
        },
        {
          id: 1,
          image: "https://picsum.photos/id/1037/1200/600",
        },
        {
          id: 1,
          image: "https://picsum.photos/id/1035/1200/600",
        },
      ],
      currentSlide: 0,
      slideInterval: null,
      direction: "right",
    };
  },
  methods: {
    setCurrentSlide(index) {
      this.currentSlide = index;
    },
    prev() {
      const index =
        this.currentSlide > 0 ? this.currentSlide - 1 : this.slides.length - 1;
      this.setCurrentSlide(index);
      this.direction = "left";
      this.startSlideTimer();
    },
    _next() {
      const index =
        this.currentSlide < this.slides.length - 1 ? this.currentSlide + 1 : 0;
      this.setCurrentSlide(index);
      this.direction = "right";
    },
    next() {
      this._next();
      this.startSlideTimer();
    },
    startSlideTimer() {
      this.stopSlideTimer();
      this.slideInterval = setInterval(() => {
        this._next;
      }, 2000);
    },
    stopSlideTimer() {
      clearInterval(this.slideInterval);
    },
  },
  mounted() {
    this.startSlideTimer();
  },
  beforeUnmount() {
    this.stopSlideTimer();
  },
};
</script>

<style scoped>
.carousel {
  display: flex;
  justify-content: center;
}

.carousel-inner {
  position: relative;
  width: 1200px;
  height: 600px;
  overflow: hidden;
}
</style>
