<template>
  <div class="content">
    <div style="background-image: url('@/assets/image/bg.png'); background-size: cover; height: 500px; width: 1000px;">inline style background image</div>
    <div class="bg">class background image</div>
    <div style="background: linear-gradient(
                    90deg,
                    rgba(26, 122, 176, 0.1) 0%,
                    rgba(26, 122, 176, 0) 100%
                  )">test inline style background</div>
    <div class="bg1">test class background</div>
  </div>
</template>

<style scoped>
.bg1 {
  background: linear-gradient(
                    90deg,
                    rgba(26, 122, 176, 0.1) 0%,
                    rgba(26, 122, 176, 0) 100%
                  )
}
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
