<template>
  <div id="app">
    <calculator></calculator>
  </div>
 
</template>

<script>
import Calculator from './components/Calculator.vue'

export default {
  name: 'App',
  components: {
    Calculator
  }
}
</script>

<style>
body{
  background-color: #31475e;
}
</style>
