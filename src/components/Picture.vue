<template>
  <img :src="logo" :alt="descricao">
</template>

<script>
export default {
  name: 'Picture',
  data() {
    return {
      logo: "/logo.png",
      descricao: "Logo do Vue.js"
    }
  }
}
</script>

<style>

</style>