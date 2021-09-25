<template>
  <div class="bg1">
    <div class="bg2">
      <Container />
    </div>
  </div>
</template>

<style scoped>
.bg2 {
  height: 100vh;
  width: 100%;
}

.bg2 {
  display: flex;
  justify-content: center;
  align-items: center;
}

.bg1::after,
.bg2::after,
.bg1::before,
.bg2::before {
  content: '';
  height: 140px;
  width: 140px;
  position: absolute;
  border-radius: 50%;
  filter: blur(60px);
}

.bg1::after {
  background: #8efcd2;
  top: 10px;
  left: 90px;
}
.bg2::after {
  background: #a68efc;
  top: 0;
  left: 0;
}
.bg1::before {
  background: #d45dd6;
  top: 50px;
}
.bg2::before {
  background: #ec8d4e;
  top: 120px;
  transform: scale(1.3);
  left: 30px;
}
</style>
