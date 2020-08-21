<template>
  <div class="wrapper">
    <div class="hero">
      <h1>Willkommen!</h1>
      <p class="subtitle">Mit Hand und Liebe gebacken.</p>
      <p class="subtitle">Seit 1933.</p>
    </div>
    <div class="bg_image" />
  </div>
</template>

<script>
export default {}
</script>

<style>
.wrapper {
  padding-top: 10%;
  height: 70vh;
  max-width: 100%;
  background-image: url('~@/assets/wip_bg.jpg');
  background-position: center center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
}

.hero {
  padding: 40px;
  color: var(--primary);
  background-color: rgba(255, 255, 255, 0.5);
}
h1 {
  font-weight: 800;
  font-size: 5em;
}

.subtitle {
  font-weight: 800;
  font-size: 2em;
}
</style>
