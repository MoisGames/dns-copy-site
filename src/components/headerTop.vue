<template>
<header id="containerHeaderTop">
<geolocationButton/>
<geolocationForm/>
<a class="headerRefs">Акции</a>
<a class="headerRefs">Магазины</a>
<a class="headerRefs">Покупателям</a>
<a class="headerRefs">Юридическим лицам</a>
<a class="headerRefs">Клуб DNS</a>
<a class="phoneHeader" href="tel:+78007707999" >8-800-77-07-999(c 7:00 до 02:00)</a>
</header>
</template>

<style>
template {
font-size: 18px;
font-weight: 400;
font-family: "PT Sans","Helvetica","Arial",sans-serif;
line-height: 1.42857;
}

.headerRefs {
margin-left: 20px;
}

.phoneHeader {
margin-left: 40px;
text-decoration: none;
}
a {
cursor: pointer;
line-height: 21px;
color: #4e4e4e;
font-size: 13px;
}
a:hover {
color: orange;
}
#containerHeaderTop {
display: flex;
}
</style>

<script>
import geolocationButton from './geolocationButton.vue';
import geolocationForm from './geolocationForm.vue';

export default {
  name: 'headerTop',
  components: {
    geolocationButton,
    geolocationForm,
  },
};
</script>
