<template>
<div class="containerGeolocation" >
  <button @click="callFormGeolocation" class="geolocationButton">
    <span id="geoLocationCity">Красноярск</span>
  </button>
  <geolocationForm/>
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
}

.geolocationButton {
display: flex;

width: 15vw;
height: 30px;
background-color: inherit;
color: inherit;
text-align: left;
align-items: end;
justify-content: end;
}

a, button:hover {
color: orangered;
}

.geolocationButton {
width: 10vw;
height: 32px;
background: url("./image/iconGeolocation.png") no-repeat left / 14px;
border: none;
}

.geolocationButton:hover {
background: url("./image/iconGeolocationOrange.png") no-repeat left / 14px;
}

#geoLocationCity {
margin-left: 20px;
font-size: 15px;
}
</style>

<script>
import geolocationForm from '../components/geolocationForm.vue';

export default {
  components: {
    geolocationForm,
  },
};

</script>
