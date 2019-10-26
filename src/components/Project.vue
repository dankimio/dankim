<template>
  <div class="flex">
    <img src="@/assets/images/logo-frogogo.svg" alt="" class="mr-4">
    <div class="flex flex-col">
      <p>{{name}}</p>
      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sed expedita minima repudiandae repellat rerum!</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Project',
  props: {
    name: String
  }
}
</script>

<style lang="postcss" scoped>
</style>
