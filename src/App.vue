<template>
  <Header />
  <PrimeiroComponente />
  <LifeCycle />
  <Pessoa />
</template>

<script>
import Header from './components/Header.vue'
import PrimeiroComponente from './components/PrimeiroComponente.vue'
import LifeCycle from './components/LifeCycle.vue'
import Pessoa from './components/Pessoa.vue'


  export default {
    name: 'app',
    components: {
      Header,
      PrimeiroComponente,
      LifeCycle,
      Pessoa,
      
    }
  }
</script>

<style> /*css global */
  body {
    background-color: #333;
    color: #fff;
  }

</style>