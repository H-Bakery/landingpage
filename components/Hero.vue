<template>
  <div class="wrapper">
    <v-card class="hero">
      <v-card-title class="title">Willkommen!</v-card-title>
      <v-card-text>
        <p class="subtitle">Seit 1933,</p>
        <p class="subtitle">mit Hand und Liebe gebacken.</p>
        <p class="subtitle">Ihre Bäckerei Heusser</p>
      </v-card-text>
    </v-card>
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
  width: 100%;
  background-image: url('~@/assets/wip_bg.jpg');
  background-position: center center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
}

.hero {
  padding: 40px;
  max-width: 42%;
  color: var(--primary);
  background-color: rgba(255, 255, 255, 0.8);
  border-radius: 10px;
}
.title {
  font-weight: 800;
  font-size: 5em;
}

.subtitle {
  font-weight: 800;
  font-size: 2em;
}

/* Small devices (landscape phones, 576px and up) */
@media (max-width: 576px) {
  .hero {
    max-width: 100%;
  }
}
</style>
