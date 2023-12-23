<template>
  <div id="containerApp">
  <div class="headerTopApp"><headerTop/></div>
  <div class="headerBotApp"><headerBot/></div>
  <homePage></homePage>
  </div>
</template>

<style>
template {
background-color: inherit;
}

#containerApp{
display: block;
max-width: 1180px;
margin: 0 auto;
font-size: 18px;
font-weight: 400;
font-family: "PT Sans","Helvetica","Arial",sans-serif;
line-height: 1.42857;
}
</style>

<script>
import headerTop from './components/headerTop.vue';
import headerBot from './components/headerBot.vue';
import homePage from './components/homePage.vue';

export default {
  name: 'App',
  components: {
    headerTop,
    headerBot,
    homePage,
  },
};

</script>

