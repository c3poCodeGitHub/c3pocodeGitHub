<template>
  <Header />
  <AllContent />
</template>

<script>
import Header from './components/Header.vue';
import AllContent from './components/AllContent.vue';

export default {
  name: 'App',
  components: {
    Header,
    AllContent
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
