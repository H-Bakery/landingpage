<template>
  <div>
    <Hero />
    <Info />
  </div>
</template>

<script>
import Hero from '~/components/Hero'
import Info from '~/components/Info'
export default {
  components: {
    Hero,
    Info,
  },
}
</script>

<style>
.page {
  height: 100vh;
}
</style>
