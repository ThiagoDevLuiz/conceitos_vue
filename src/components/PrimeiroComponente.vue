<template>
  <div>
    <h1>Hello Vue!</h1>
    <p>My name is {{ name }} and i'm {{ profissao }}</p>
  </div>
</template>

<script>
export default {
  name: 'PrimeiroComponente',
  data() {
    return {
      name: 'Thiago Luiz',
      profissao: 'garoto de programa'
    };
  }
};
</script>

<style scoped>

</style>