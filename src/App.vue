<template>
<div>
  <FirstBody></FirstBody>
</div>
</template>

<script>
import FirstBody from './components/FirstBody.vue'



export default {
  name: 'App',
  components: {
    FirstBody
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
