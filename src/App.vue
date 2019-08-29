<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
body {
  height: 100%;
  background-color: rgba(238,156,167,.5);
  /* background-image: url('assets/ballon.jpg') ; */
  /* background-repeat: no-repeat; */
  /* background-position: center ; */
  font-size: 1em;
}
html {
  font-size: 100%;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
@import './style/common.scss';
</style>
