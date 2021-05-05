<template>
  <div id="app">
    <FirstComponent/>
    <HeaderComponent/>
  </div>
</template>

<script>
import FirstComponent from './components/FirstComponent.vue'
import HeaderComponent from './components/HeaderComponent.vue'


export default {
  name: 'App',
  components: {
    FirstComponent,
    HeaderComponent
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
