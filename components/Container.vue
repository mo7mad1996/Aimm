<template>
  <div class="Container">
    <SiteText />
    <OpenVideo />
  </div>
</template>

<style scoped lang="scss">
.Container {
  min-height: 90vh;
  width: 90vw;
  background-image: linear-gradient(135deg, rgba(255, 255, 255, 0.3), white);
  padding: 30px;
  border-radius: 30px;
  z-index: 1;
  position: relative;

  display: flex;
}

@media (max-width: 170vh) {
  .Container {
    display: block;
  }
}
</style>

<script>
  console.log(
    `%c This site UI form  %c  https://dribbble.com/shots/16133682-Aimm-2-Hero-header-concept %c Created By Mohammed Ibrahem ♥ %c`,
    'background-image: linear-gradient(90deg, #35495e, #c4a5da ) ; color: #dc080d; border-radius: 10px 0 0 10px;',
    'background: #c4a5da; color: #333; border-radius: 0 0 0 0;',
    'background-image: linear-gradient(90deg, #c4a5da, #4e74fd ) ; color: #f00; border-radius: 0 10px 10px 0;',
    'background:transparent'
  )
</script>