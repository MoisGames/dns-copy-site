<template>
<div id="containerFormGeolocation">
    <form id="formGeolocation" ref="formRefGeolocation">
        <div id="containerYourCity">
            <div id="yourCity">Ваш город
              </div>
            </div>
                <div id="containerSearchCityGeolocation">
                    <input id="searchCityGeolocation" placeholder="Найти город">
                </div>
    </form>
</div>
    </template>

<style>
#containerFormGeolocation {
display: none;
align-items: center;
background-color: rgb(173, 32, 32);
}

#formGeolocation {
/*
display: flex;
flex-direction: column;
min-width: 200px;
max-width: 100%;
height: 70vh;
border: solid rgb(245, 243, 243) 10px;
border-radius: 1% 1% 1% 1%;
box-shadow: 0 16px 24px 0 rgba(0,0,0,.32);
overflow: hidden;
align-self: center;
justify-content: start;
background: #fff; */
border-radius: 8px;
background: #fff;
min-width: 200px;
max-width: 100%;
height: 75vh;
box-shadow: 0 16px 24px 0 rgba(0,0,0,.32);
overflow: hidden;
align-self: center;
display: flex;
flex-direction: column;
}

#containerYourCity {
display: flex;
width: inherit;
height: 6vh;
background: border-box rgb(245, 243, 243);
border-radius: 1% 0 0 1%;
align-items: start;
justify-content: start;
}

#yourCity {
display: flex;
width: 45vw;
height: 4vh;
text-align: left;
font-weight: 600;
margin: 15px 0 0 15px;
}

#containerSearchCityGeolocation {
display: flex;
width: 45vw;
height: 10vh;
justify-content: center;
align-items: center;
}

#searchCityGeolocation {
display: flex;
width: 43vw;
height: 4vh;
border: solid rgb(245, 243, 243) 1px;
border-radius: 10px;
background-color: rgb(245, 243, 243);
}

#searchCityGeolocation::active {
background-color:rgb(255, 255, 255);
}

#searchCityGeolocation:hover {
background-color: rgb(216, 214, 214);
}
</style>

<script>
/*
const app = new Vue({
    el: "#wrapperFormGeolocation",
    methods:{
    callFormGeolocation: function(){
      this.$refs.formGeolocation = innerHTML;
    },
}
}); */

</script>
