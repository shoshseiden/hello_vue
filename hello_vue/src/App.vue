<template>
  <div id="app">
    <MyHello/>
  </div>
</template>

<script>
import MyHello from './components/MyHello.vue'

export default {
  name: 'app',
  components: {
    MyHello
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
