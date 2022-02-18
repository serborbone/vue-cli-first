<template>
  <div id="app">
    <myTitle></myTitle>
    <NewHero></NewHero>
  </div>
</template>

<script>
import myTitle from './components/myTitle.vue'
import NewHero from './components/NewHero.vue'


export default {
  name: 'App',
  components: {
    myTitle,
    NewHero,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background-color: #d0f5f5;
}
</style>
