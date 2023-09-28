<style>
.containerGeolocation {
border: solid 5px purple;
width: 10%;
height: 10%;
display: flex;
flex-direction: row;
}
.geolocationButton {
border: groove 5px red;
background-color: inherit;
color: inherit;
text-align: center;
}
#iconGeo {
width: 16px;
height: 16px;
}
</style>
<template>
  <div class="containerGeolocation">
<button v-on:click="formButton" class="geolocationButton">
<img src="./image/iconGeolocation.png" id="iconGeo">
  Красноярск
</button>
  </div>
</template>

<script>

</script>
