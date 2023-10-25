<template>
  <div id="containerApp">
  <div class="headerTopApp"><headerTop/></div>
  <div class="headerBotApp"><headerBot/></div>
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
display: block;
max-width: 70vw;
height: 100%;
margin: 2vh 0 0 calc(0vw + 18vw);
font-size: 18px;
font-weight: 400;
font-family: "PT Sans","Helvetica","Arial",sans-serif;
line-height: 1.42857;
}
</style>
