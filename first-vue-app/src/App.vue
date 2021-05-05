<template>
  <div id="app">
    <HeaderComponent/>
    <div class="logo">
      <img alt="Google Logo" src="./assets/logo.png">
    </div>
    <SearchComponent/>
    <ButtonsComponent/>
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import SearchComponent from './components/SearchComponent.vue'
import ButtonsComponent from './components/ButtonsComponent.vue'


export default {
  name: 'App',
  components: {
    HeaderComponent,
    SearchComponent,
    ButtonsComponent
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
}
.logo{
    justify-content: center;
    position: relative;
    display: inline-flex;
    width: 100%;
    height: 5.7rem;
    margin: 0 auto;
    margin-top: 6rem;
  }
</style>
