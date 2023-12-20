<template>
  <div>
    <Site></Site>
  </div>
</template>

<script>
import Site from './components/Website/Site.vue'

export default {
  name: 'App',
  components: {
    Site
  },
  data() {
    return {
    }
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
  margin-top: 0;
}
</style>
