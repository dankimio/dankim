<template>
  <div id="app">
    <About msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import About from './components/About.vue'

export default {
  name: 'app',
  components: {
    About
  }
}
</script>

<style src="./assets/tailwind.css">
</style>
