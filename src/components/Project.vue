<template>
  <div class="flex items-start">
    <img :src="src" :alt="name" class="w-12 h-12 mr-5">

    <div class="flex flex-col">
      <p class="mb-1 md:text-lg text-gray-900">
        {{name}}
      </p>
      <p class="text-sm md:text-base text-gray-700">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sed expedita minima repudiandae!
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Project',
  props: {
    name: String,
    src: String
  }
}
</script>

<style lang="postcss" scoped>
</style>
