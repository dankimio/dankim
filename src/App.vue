<template>
  <div id="app" class="container px-6 pt-6 md:pt-32 lg:pt-48 md:max-w-lg lg:max-w-xl">
    <About msg="Welcome to Your Vue.js App"/>
    <Project name="Frogogo" />
  </div>
</template>

<script>
import About from './components/About.vue'
import Project from './components/Project.vue'

export default {
  name: 'app',
  components: {
    About, Project
  }
}
</script>

<style src="./assets/tailwind.css">
</style>
