<template>
  <div class="container mt-3">
    <Header />
    <Formulario />
  </div>
</template>

<script>
  
  import Header from "./components/Header.vue"
  import Formulario from "./components/Formulario.vue"
  export default {
    components: {
      Formulario,
      Header,
    }
  }
</script>

<style scoped>
  body {
    margin: 0px 2rem;
  }
</style>