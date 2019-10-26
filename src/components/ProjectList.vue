<template>
  <div>
    <h2 class="mb-4 md:text-lg text-gray-900 font-medium">
      What I've been working on
    </h2>

    <Project
      v-for="project in projects"
      :name="project.name"
      :key="project.name"
      class="mb-6 md:mb-8" />
  </div>
</template>

<script>
import Project from './Project.vue'

export default {
  name: 'ProjectList',
  components: { Project },
  data() {
    return {
      projects: [
        { name: 'Frogogo' },
        { name: 'Chisto' }
      ]
    }
  }
}
</script>

<style lang="postcss" scoped>
</style>
