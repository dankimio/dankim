<template>
  <div>
    <h1 class="mb-5 text-4xl md:text-5xl font-bold text-gray-900">
      Hi, I'm Dan Kim.
    </h1>
    <p class="mb-5 text-2xl md:text-3xl text-gray-700">
      I write software and design interfaces.
    </p>
    <p class="mb-6 md:mb-8 md:text-lg text-gray-800">
      Currently based in Moscow, Russia
    </p>

    <div v-if="false">
      {{msg}}
    </div>
  </div>
</template>

<script>
export default {
  name: 'About',
  props: {
    msg: String
  }
}
</script>

<style scoped lang="css">
</style>
