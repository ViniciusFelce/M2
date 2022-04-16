<template>
  <div>
    <InterContainer/>
    <FixoContainer/>
    <TvContainer/>
    <Pedido/>
  </div>      
</template>

<script>
  import InterContainer from './components/InterContainer.vue'
  import FixoContainer from './components/FixoContainer.vue'
  import TvContainer from './components/TvContainer.vue'
  import Pedido from './components/Pedido.vue'

  export default {
    name: 'App',
    components: {
      InterContainer,
      FixoContainer,
      TvContainer,
      Pedido
    }
  }
</script>

<style>
#app {
  font-family: 'Roboto', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
  body {
    margin: 0%;
    height: 100vh;
  }
</style>
