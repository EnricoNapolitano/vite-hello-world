<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'
export default {
  name: 'App',
  components: {
    AppTitle,
    AppHero,
  }
}
</script>

<template>
  <div class="container">
    <app-title></app-title>
    <app-hero></app-hero>
  </div>
</template>

<style>
.container {
  margin: 0 auto;
  width: 1600px;
}

img {
  max-width: 100%;
}
</style>