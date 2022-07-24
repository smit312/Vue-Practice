<template>
<h1> Provide | Inject</h1>
<h3> Name {{name}}</h3>
 <ComponentA />
</template>

<script>
import ComponentA from './components/ComponentA.vue'

export default {
  name: 'App',
  components: {
    ComponentA
},
data() {
  return{
name : "Smit"}
},
provide() {
  return{
  Uname : this.name}
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
