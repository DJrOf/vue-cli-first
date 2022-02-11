<template>
<div>
   <Header/>
</div>


</template>

<script>
import Header from './components/Header.vue'

export default {
  name: 'App',
  components: {
    Header
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
