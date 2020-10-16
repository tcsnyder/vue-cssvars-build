<template>
  <span>Works?</span>
</template>

<script>
export default {
  name: 'App',
  setup () {
    var color = '#4488dd'
    return { color }
  }
}
</script>

<style vars="{color}">
span{
  background-color: var(--color)
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
