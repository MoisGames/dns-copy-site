<template>
<header id="containerHeaderTop">
<geolocationButton/>
<geolocationForm/>
<a class="headerRefs">Акции</a>
<a class="headerRefs">Магазины</a>
<a class="headerRefs">Покупателям</a>
<a class="headerRefs">Юридическим лицам</a>
<a class="headerRefs">Клуб DNS</a>
</header>
</template>

<style>
.headerRefs {
margin-left: 20px;
font-size: 13px;
}
a:hover {
text-decoration: orange;
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
