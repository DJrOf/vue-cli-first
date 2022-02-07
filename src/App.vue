<template>
  <div id="app">
    <header>
      <h1>La mia prima app con Vue CLI!<h1>
    </header>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss">
#app {
  
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
