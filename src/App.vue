<template>
  <div id="app" class="container px-6 pt-6 md:pt-32 md:max-w-lg lg:max-w-xl">
    <About />

    <Divider />

    <ProjectList />

    <Divider />

    <Photography />
  </div>
</template>

<script>
import About from './components/About.vue'
import Divider from './components/Divider.vue'
import ProjectList from './components/ProjectList.vue'
import Photography from './components/Photography.vue'

export default {
  name: 'app',
  components: {
    About, Divider, ProjectList, Photography
  }
}
</script>

<style src="./assets/tailwind.css">
</style>
