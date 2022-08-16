<template>
  <div id="app">
    <h2>My Vue.js App</h2>
    <super-marquee content="SuperMarquee says 'Hello' to Vue.js."></super-marquee>
  </div>
</template>

<script>

import 'sp-supermarquee/dist/SuperMarqueeWC.js';

export default {
  name: 'App',
  components: {}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
super-marquee {
  font-family: 'Courier New', Courier, monospace;
  font-size: larger;
  font-weight: bold;
}
</style>
