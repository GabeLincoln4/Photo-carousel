<template>
  <photo-carousel></photo-carousel>
</template>

<script>
import PhotoCarousel from './components/carousel.vue'

export default {
  name: 'App',
  components: {
    PhotoCarousel
  }, 
  data() {
    photoArray = [
      "https://picsum.photos/id/250/200/300",
      "https://picsum.photos/id/290/200/300",
      "https://picsum.photos/id/228/200/300",
      "https://picsum.photos/id/285/200/300",
      "https://picsum.photos/id/256/200/300",
      "https://picsum.photos/id/238/200/300",
      "https://picsum.photos/id/293/200/300",
      
    ]
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
