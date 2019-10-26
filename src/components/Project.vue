<template>
  <div class="flex items-start">
    <img :src="src" :alt="name" class="w-12 h-12 mr-5">

    <div class="flex flex-col">
      <a :href="url" class="mb-1 md:text-lg text-gray-900">
        {{name}}

        <img src="@/assets/images/icon-arrow.svg" class="inline-block ml-2 w-3 h-3">
      </a>
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
    src: String,
    url: String
  }
}
</script>

<style lang="postcss" scoped>
</style>
