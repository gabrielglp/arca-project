<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <TesteTestado/>
  </div>
</template>

<script>
import TesteTestado from '@/components/TesteTestado.vue'

export default {
  name: 'App',
  components: {
    TesteTestado
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
