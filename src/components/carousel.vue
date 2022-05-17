<template>
  <img :src="photo" />
</template>

<script>
export default {
  name: 'PhotoCarousel',
  props: {
    photo: {
      type: String
    }
  }
}
</script>

<style>

</style>
