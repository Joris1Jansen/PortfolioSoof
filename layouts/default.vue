<template>
  <div>
    <the-header></the-header>
    <nuxt></nuxt>
  </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue'

export default {
  components: {
    TheHeader,
  },
}
</script>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 62.5%;
  background: #121212;
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
</style>
