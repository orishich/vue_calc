<template>
  <div id="app">
    <Calcapp/>
  </div>
</template>

<script>
import Calcapp from './components/calc.vue'

export default {
  name: 'app',
  components: {
    Calcapp
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #213242;
  margin-top: 60px;
}
</style>
