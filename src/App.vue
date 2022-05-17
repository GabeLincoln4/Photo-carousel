<template>
  <photo-carousel></photo-carousel>
</template>

<script>
import PhotoCarousel from './components/carousel.vue'

export default {
  name: 'App',
  components: {
    PhotoCarousel
  }
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
