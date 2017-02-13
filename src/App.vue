<template>
  <div class="app">
    <com-nav></com-nav>
    <com-main></com-main>
    <com-footer></com-footer>
  </div>
</template>

<script>
  import comNav from './components/Nav.vue'
  import comMain from './components/Main.vue'
  import comFooter from './components/Footer.vue'

  export default {
    name: 'app',
    components: {
      comNav,
      comMain,
      comFooter
    },
    data () {
      return {
        msg: 'Welcome to Your Vue.js App'
      }
    }
  }
</script>

<style>
.app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
