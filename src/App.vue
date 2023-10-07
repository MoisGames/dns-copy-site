<template>
  <div class="wrapperApp">
  <geolocationButton/>
  </div>
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
#app{
display: flex;
width: 40vw;
height: 100%;
margin: 2vh 0 0 calc(0vw + 18vw);
}
</style>
