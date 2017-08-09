<template>
  <div id="app">
    <button class="prefix-btn prefix-btn-primary">button with <code>prefix-</code> class</button>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss">
$icon-font-path: "~bootstrap-sass/assets/fonts/bootstrap/";
@import '~bootstrap-sass/assets/stylesheets/bootstrap';
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
