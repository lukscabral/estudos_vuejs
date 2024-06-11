<template>
  <h1>Olá Vue!</h1>
  <p>Meu nome é {{ nome }} e trabalho como {{ profissao }}</p>
  <MultiplosEventos/>
</template>

<script>
  import MultiplosEventos from './MultiplosEventos.vue';

  export default {
    name: 'PrimeiroComponente',
    components: {
      MultiplosEventos
    },
    data() {
      return {
        nome: 'Lucas',
        profissao: 'programador'
      }
    }

  }
</script>