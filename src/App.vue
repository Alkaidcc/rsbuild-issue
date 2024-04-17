<template>
  <div class="content">
    <div style="background-image: url('@/assets/image/bg.png'); background-size: cover; height: 500px; width: 1000px;">inline style background</div>
    <div class="bg">class background</div>
  </div>
</template>

<style scoped>
.content {
  display: flex;
  min-height: 100vh;
  line-height: 1.1;
  text-align: center;
  flex-direction: column;
  justify-content: center;
}

.bg {
  background-image: url('@/assets/image/bg.png');
  background-size: cover;
  height: 500px;
  width: 1000px;
}
</style>
