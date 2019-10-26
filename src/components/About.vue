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

    <OutlinedButton class="mr-3 md:mr-4">
      dankimio
    </OutlinedButton>

    <OutlinedButton class="mr-3 md:mr-4">
      dankimio
    </OutlinedButton>

    <div v-if="false">
      {{msg}}
    </div>
  </div>
</template>

<script>
import OutlinedButton from './OutlinedButton.vue'

export default {
  name: 'About',
  components: { OutlinedButton },
  props: {
    msg: String
  }
}
</script>

<style scoped lang="css">
</style>
