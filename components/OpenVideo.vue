<template>
  <video autoplay loop ref="video">
    <source src="/start.mp4" />
  </video>
</template>

<script>
export default {
  mounted() {
    this.$refs.video.play()
  },
}
</script>

<style scoped>
video {
  border-radius: 10px;
  display: block;
  max-height: 80vh;
  max-width: 100%;
  object-fit: cover;
}
</style>
