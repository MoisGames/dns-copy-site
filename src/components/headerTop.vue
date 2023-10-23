<template>
<header id="containerHeaderTop">
<geolocationButton/>
<geolocationForm/>
<a class="headerRefs" href="https://www.dns-shop.ru/actions">Акции
  <svg height="10" width="10">
   <circle cx="5" cy="5" r="1" stroke="orange" stroke-width="3" fill="orange" />
  </svg>
</a>
<a class="headerRefs" href="https://www.dns-shop.ru/shops/krasnoyarsk/">Магазины</a>
<div class="headerRefs" id="buyersDropdown">Покупателям
  <div class="dropdownContent">
    <a class="dropdownRefs" href="https://www.dns-shop.ru/help/delivery/">Доставка</a>
    <a class="dropdownRefs" href="https://prozapass.ru/">Бонусная программа</a>
    <a class="dropdownRefs" href="https://www.dns-shop.ru/order/check-order-status/">Узнать статус заказа</a>
    <a class="dropdownRefs" href="https://www.dns-shop.ru/service-center/exchange-and-returns/">Обмен, возврат, гарантия</a>
    <a class="dropdownRefs" href="https://www.dns-shop.ru/credit/">Кредиты</a>
    <a class="dropdownRefs" href="https://www.dns-shop.ru/service-center/">Сервисные центры</a>
  </div>
</div>
<a class="headerRefs" href="https://www.dns-shop.ru/help/legal-entities/">Юридическим лицам</a>
<a class="headerRefs" href="https://club.dns-shop.ru/">Клуб DNS</a>
<a class="phoneHeader" href="tel:+78007707999" >8-800-77-07-999 (c 7:00 до 02:00)</a>
</header>
</template>

<style>
html {
    width: 100%;
    position: relative;
    border: none;
    background-image: none;
}
#containerHeaderTop {
font-size: 16px;
font-family: "PT Sans","Helvetica","Arial",sans-serif;
line-height: 21px;
color: #4e4e4e;
font-weight: normal;
background-color: inherit;
}

.headerRefs {
margin-right: 22px;
font-size: inherit;
display: block;
}
#buyersDropdown {
position: relative;
display: inline-block;
}
.phoneHeader {
margin-left: 40px;
text-decoration: none;
font-size: inherit;
}
a {
cursor: pointer;
line-height: 21px;
font-size: inherit;
color: #4e4e4e;
text-decoration: none;
}
a:hover,.dropdownRefs:hover {
color: orange;
}
#containerHeaderTop {
display: flex;
}

.arrowUpDown {
  background: url('../assets/image/arrowDown.png') no-repeat right / 10px;
  width: 20px;
}

.arrowUpDown:hover {
  background: url('../assets/image/arrowUp.png') no-repeat right / 10px;
}

.dropdownContent {
display: none;
position: absolute;
flex-flow: column nowrap;
box-shadow: 0 6px 8px rgba(89,16,0,.08);
background-color: #fff;
color: inherit;
text-align: left;
align-items: start;
justify-content: start;
border: none;
width: 12vw;
height: 25vh;
justify-content: start;
margin: 10px 0 0 10px;
border-radius: 10px;
border: #4e4e4e 0,1px solid;
}

.dropdownRefs {
margin: 15px 15px 0px 15px;
}

#buyersDropdown:hover .dropdownContent {
  display: flex;
}

#buyersDropdown {
background: url('../assets/image/arrowDown.png') no-repeat 100% 35% / 10px;
width: 110px;
}

#buyersDropdown:hover {
background: url('../assets/image/arrowUp.png') no-repeat 100% 35% / 10px;
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
