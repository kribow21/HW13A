<template>
<div>
  <FirstHeader></FirstHeader>
  <FirstBody></FirstBody>
  <FirstFooter></FirstFooter>
</div>
</template>

<script>
import FirstHeader from './components/FirstHeader.vue'
import FirstBody from './components/FirstBody.vue'
import FirstFooter from './components/FirstFooter.vue'


export default {
  name: 'App',
  components: {
    FirstHeader,
    FirstBody,
    FirstFooter
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
