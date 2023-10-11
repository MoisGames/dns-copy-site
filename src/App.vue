<template>
  <div id="containerApp">
  <headerTop/>
  <headerBot/>
  </div>
</template>

<script>
import headerTop from './components/headerTop.vue';
import headerBot from './components/headerBot.vue';

export default {
  name: 'App',
  components: {
    headerTop,
    headerBot,
  },
};
</script>


<style>
#containerApp{
display: flex;
width: 70vw;
height: 100%;
margin: 2vh 0 0 calc(0vw + 18vw);
font-size: 16px;
font-family: Arial, Helvetica, sans-serif;
color: #4e4e4e;
}
</style>
