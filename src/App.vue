<template>
  <div id="app">
    <Pokemon />
  </div>
</template>

<script>
import Pokemon from './components/Pokemon.vue'

export default {
  components: {
    Pokemon
  }
}
</script>

<style lang="scss">
  @import url('https://use.fontawesome.com/releases/v5.8.2/css/all.css');

  body {
    margin: 0;
    padding: 0;
  }
</style>
