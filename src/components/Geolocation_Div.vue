<template>
<header>
  <div id="geolocation-div">
    <YandexMap :settings="settings" :coordinates="[32, 50]">
    <!--Markers-->
    </YandexMap>
  </div>
  <div id="text">
    Работает или нет??????????????????????????
  </div>
</header>
</template>

<script>
export default {
  name: 'Geolocation_Div',
  props: {
    msg: String
  }
}
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
