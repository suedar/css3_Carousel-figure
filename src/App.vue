<template>
  <div id="app">
    <HelloWorld>
      <img src="https://randomm.cdn.bcebos.com/123.jpeg" alt="">
      <img src="https://randomm.cdn.bcebos.com/123.jpeg" alt="">
      <img src="https://randomm.cdn.bcebos.com/123.jpeg" alt="">
    </HelloWorld>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss">
#app {
}
</style>
