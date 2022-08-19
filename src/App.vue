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
  background: rgb(113, 113, 117);
 }
</style>
