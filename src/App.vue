<template>
  <geolocationButton/>
</template>

<script>
import geolocationButton from './components/geolocationButton.vue';
export default {
  name: 'App',
  components: {
    geolocationButton,
  },
};
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
