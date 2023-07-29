<template>
  <PrimeiroComponente />
  <LifeCycle />
  <Pessoa />
</template>

<script>
import PrimeiroComponente from './components/PrimeiroComponente.vue';
import LifeCycle from './components/LifeCycle.vue';
import Pessoa from './components/Pessoa.vue';

export default {
  name: 'App',
  components: { 
    PrimeiroComponente,
    LifeCycle,
    Pessoa,
  }
};
</script>

<style lang="scss">
  body {
    background-color: #333;
    color: #ccc;
  }

  a {
    color: red;
    text-decoration: none;
    font-weight: bold;
    transition: all 0.3s ease-in-out;
    &:hover {
      color: blue;
    }
  }
</style>
