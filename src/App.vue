<template>
  <div class="logo">
    <div class="logo-bg"></div>
    <h1>
      <a href="#">侗 语</a>
    </h1>
  </div>
</template>

<script setup>
</script>

<style scoped>
.logo {
  position: relative;
  height: 6em;
  padding: 1.5em;

}

.logo-bg {
  position: absolute;
  width: 100%;
  height: 100%;
  background: linear-gradient(-45deg, #bd34fe 50%, #47caff 50%);
  filter: blur(66px);

}
</style>
