<template>
  <a href="#" class="inline-block text-center px-3 py-1 border border-gray-400 text-gray-800 tracking-wide cursor-pointer hover:bg-gray-700 hover:text-white hover:border-gray-700">
    <slot></slot>
  </a>
</template>

<script>
export default {
  name: 'OutlinedButton',
  props: {}
}
</script>
