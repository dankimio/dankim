<template>
  <div>
    <h2 class="mb-4 md:text-lg text-gray-900 font-medium">
      What I've been working on
    </h2>

    <Project name="test" class="mb-6" />
    <Project name="test" class="mb-6" />
  </div>
</template>

<script>
import Project from './Project.vue'

export default {
  name: 'ProjectList',
  components: { Project }
}
</script>

<style lang="postcss" scoped>
</style>
