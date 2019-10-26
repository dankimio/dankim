<template>
  <div id="app" class="container px-6 pt-6 md:pt-32 lg:pt-48 md:max-w-lg lg:max-w-xl">
    <About msg="Hello, world!"/>

    <Divider />

    <ProjectList />

    <Divider />
  </div>
</template>

<script>
import About from './components/About.vue'
import Divider from './components/Divider.vue'
import ProjectList from './components/ProjectList.vue'

export default {
  name: 'app',
  components: {
    About, Divider, ProjectList
  }
}
</script>

<style src="./assets/tailwind.css">
</style>
