<template>
  <div>
    <h1></h1>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus, inventore. Cum, repudiandae.
    </p>
    {{msg}}
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped lang="css">
</style>
