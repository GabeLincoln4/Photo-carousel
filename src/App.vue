<template>
  <photo-carousel v-for="(photo, index) in photoArray" :visibleSlide="visibleSlide" :key="photo" :index="index" :photo="photo"></photo-carousel>
</template>

<script>
import PhotoCarousel from './components/carousel.vue'

export default {
  name: 'App',
  components: {
    PhotoCarousel
  }, 
  data() {
    return {
      photoArray: [
      "https://picsum.photos/id/250/200/300",
      "https://picsum.photos/id/290/200/300",
      "https://picsum.photos/id/228/200/300",
      "https://picsum.photos/id/257/200/300",
      "https://picsum.photos/id/256/200/300",
      "https://picsum.photos/id/238/200/300",
      "https://picsum.photos/id/293/200/300",
      ],
      visibleSlide: 0,
    }
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
