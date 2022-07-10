<template>
  <transition :name="transitionEffect">
    <div class="carousel-item" v-show="currentSlide === index">
      <img :src="slide.image" alt="DooItems" />
      <h1>
        <span
          >Enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi
          ut aliquip ex ea commodo consequat.</span
        >
      </h1>
      <span><button>log in</button></span>
    </div>
  </transition>
</template>

<script>
export default {
  props: ["slide", "currentSlide", "index", "direction"],
  computed: {
    transitionEffect () {
        return this.direction === "right" ? "slide-out" : "slide-in"
    }
  }
};
</script>

<style scoped>
.carousel-item {
  position: absolute;
  object-fit: cover;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
}

span {
  position: absolute;
  top: 200px;
  left: 100px;
  color: #bbb black;
  font: size 12rem;
  -webkit-text-stroke-width: 1px;
  -webkit-text-stroke-color: black;
}

span button {
  position: absolute;
  top: 100px;
  left: 20px;
  width: 100px;
  padding: 12px 20px;
  border-radius: 10px;
  border: 1.5px solid red;
  font-size: 16px;
}

span button:hover {
  opacity: 0.9;
}

.slide-in-enter-active,
.slide-in-leave-active,
.slide-out-enter-active,
.slide-out-leave-active
 {
    transition: all 1s ease-in-out;
}

.slide-in-enter-from{
    transform: translateX(-100%)
}

.slide-in-leave-to {
    transform: translateX(100%);
}


.slide-out-enter-from{
    transform: translateX(100%)
}

.slide-out-leave-to {
    transform: translateX(-100%);
}


</style>
