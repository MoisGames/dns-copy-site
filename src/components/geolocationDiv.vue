<template>
  <header>
    <div id="geolocationBoxDiv">
      <YandexMap :settings="settings" :coordinates="[32, 50]">
  --------
      </YandexMap>
      <YandexMarker>
  ---------
      </YandexMarker>
    </div>
    <div id="text">
      Работает или нет??????????????????????????
    </div>
  </header>
  </template>
<script>
import {YandexMap, YandexMarker} from 'vue-yandex-maps';

export default {
  name: 'geolocationDiv',
  props: {
    msg: String,
  },
  components: {
    YandexMap, YandexMarker},
};

</script>
  <style scoped>
  h3 {
    margin: 40px 0 0;
  }
  ul {
    list-style-type: none;
    padding: 0;
  }
  li {
    display: inline-block;
    margin: 0 10px;
  }
  a {
    color: #42b983;
  }
</style>
