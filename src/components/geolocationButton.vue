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
width: 300px;
height: 30px;
flex-direction: row;
align-items: start;
justify-content: start;
color: #4e4e4e;
font-size: 16px;
font-family: "PT Sans","Helvetica","Arial",sans-serif;
line-height: 21px;
color: #4e4e4e;
font-weight: normal;
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
background: url("../assets/image/iconGeolocation.png") no-repeat left / 13px;
border: none;
}

.geolocationButton:hover {
background: url("../assets/image/iconGeolocationOrange.png") no-repeat left / 13px;
color: orangered;
}

#geoLocationCity {
margin-left: 20px;
}
</style>

<script>

</script>
