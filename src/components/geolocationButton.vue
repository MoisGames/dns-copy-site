<template>
<div class="containerGeolocation" >
  <button @click="''" class="geolocationButton">
    <span id="geoLocationCity">Красноярск</span>
  </button>
</div>

</template>

<style>
.containerGeolocation {
display: flex;
width: 15vw;
height: 30px;
flex-direction: row;
align-items: start;
justify-content: start;
color: #4e4e4e;
}

.geolocationButton {
display: flex;
width: 15vw;
height: 15px;
background-color: inherit;
color: inherit;
text-align: left;
align-items: start;
justify-content: start;
background: url("./image/iconGeolocation.png") no-repeat left / 10px;
border: none;
}

a, button:hover {
color: orangered;
}

.geolocationButton:hover {
background: url("./image/iconGeolocationOrange.png") no-repeat left / 10px;
}

#geoLocationCity {
margin-left: 20px;
font-size: 12px;
}
</style>

<script>

</script>
