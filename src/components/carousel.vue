<template>
  <div v-show="visibleSlide===index">
    <img :src="photo" />
  </div>
</template>

<script>
export default {
  name: 'PhotoCarousel',
  props: ['visibleSlide','index', 'photo']
}
</script>

<style>

</style>
