<template>
<div id="wrapperFormGeolocation">
    <form id="formGeolocation" ref="formRefGeolocation">
        <div id="wrapperYourCity">
            <div id="yourCity">Ваш город</div>
            </div>
    </form>
</div>
    </template>

<style>

#wrapperFormGeolocation{
display: flex;
align-items: start;
justify-content: center;
font-family: Arial, Helvetica, sans-serif;
margin: 10vh 0 0 5vh;
}

#formGeolocation {
display: flex;
width: 45vw;
height: 70vh;
border: solid rgb(245, 243, 243) 10px;
border-radius: 1% 1% 1% 1%;
align-items: start;
justify-content: start;

}

#wrapperYourCity {
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
width: 10vw;
height: 4vh;
text-align: left;
font-weight: 600;
font-size: 18px;
margin: 15px 0 0 15px;
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
