<template>
<nav class="headerSearchContainer">
<div class="headerBotContainer">
    <div class="containerHeaderBottomLogoCatalog">
        <a class="containerLogoHeaderBottom">
            <div id="headerLogo">
            </div>
        </a>
            <button class="menuCatalogButton">
                <span class="headerBottomCatalogTittle">Каталог</span>
                    <svg class="headerBottomArrowSvg" width="24px" height="24px" fill="none" view-box="0 0 24 24">
                    <path d="M16.594 8.578L18 9.984L12 15.984L6 9.984L7.406
                 8.578L12 13.172L16.594 8.578Z" fill="#fff"></path></svg>
            </button>
    </div>
<div class="inputSearchContainer">
    <input class="searchInput" placeholder="Поиск по сайту" type="search"
    onfocus= "document.querySelector('html').style.backgroundColor = '#e7e7e7'"
    onblur= "document.querySelector('html').style.backgroundColor = '#fff'">
        <button class="iconSearchContainer">
        </button>
</div>
  <div class="buttonContainer">
    <button class="buttonHeaderBotContainer">
      <img class="iconButtonBottomHeader" id="comparisonIcon">
      <div class="textButtonBottomHeader">Сравнение</div>
    </button>
    <button class="buttonHeaderBotContainer">
      <img class="iconButtonBottomHeader" id="iconHeart">
      <div class="textButtonBottomHeader">Избранное</div>
    </button>
    <button class="buttonHeaderBotContainer">
      <img class="iconButtonBottomHeader" id="iconShoppingCart">
      <div class="textButtonBottomHeader">Корзина</div>
    </button>
    <button class="buttonHeaderBotContainer">
      <img class="iconButtonBottomHeader" id="iconEntrance">
      <div class="textButtonBottomHeader">Войти</div>
    </button>
  </div>
</div>
</nav>
</template>

<style>
template {
background-color: inherit;
}


.headerSearchContainer {
  background-color: inherit;
    transition: background 200ms ease-out 0s;
    z-index: 2;
    height: 96px;
    box-sizing: content-box;
    font-size: 14px;
    display: flex;
    align-items: center;
    justify-content: start;
}

.headerBotContainer {
  display: flex;
    align-items: center;
    position: relative;
    white-space: nowrap;
    width: 1180px;
    margin: 0 auto;
    height: 100%;
    box-sizing: content-box;
    max-height: 64px;
    font-size: 14px;
}

.containerHeaderBottomLogoCatalog {

    z-index: 105;
    display: flex;
    align-items: center;
    box-sizing: content-box;
    text-align: left;
    max-height: 64px;
    float: left;
    background: linear-gradient(0deg, #fc8507 0%, #ffa218 100%);
    padding-right: 12px;
    border-radius: 12px;
    position: relative;
    width: 275px;
    background-color: inherit;
}

.containerLogoHeaderBottom  {
    height: 64px;
    display: flex;
    width: 30%;
    padding-left: 20px;
    padding-right: 20px;
    align-items: center;
    border-top-left-radius: 12px;
    border-bottom-left-radius: 12px;
    transition: .2s;
    cursor: pointer;
}

.containerLogoHeaderBottom:hover {
transition: .2s;
background: rgba(255,255,255,.12);
}

#headerLogo {
    transition: all 300ms ease-in 0s;
    display: inline-block;
    height: 20px;
    vertical-align: middle;
    width: 80px;
    position: relative;
    background: url('../assets/image/Dns-shop_logo.svg') no-repeat center left;
}

.menuCatalogButton {
    transition: opacity 300ms ease-in 300ms;
    opacity: 1;
    border-radius: 8px;
    background: rgba(255,255,255,.12);
    box-shadow: 0 6px 8px rgba(89,16,0,.08);
    color: #fff;
    cursor: pointer;
    text-align: center;
    visibility: visible;
    display: flex;
    flex-direction: row;
    font-weight: bold;
    font-size: 16px;
    margin-bottom: 0;
    padding: 10px 16px 10px 20px;
    justify-content: flex-end;
    align-items: flex-end;
    border: none;
    margin-left: 24px;
}

.menuCatalogButton:hover {
background: rgba(255,255,255,.22);
box-shadow: 0 6px 8px rgba(89,16,0,.08);
}

.headerBottomArrowSvg {
    transition: all 200ms ease-out 0ms;
}

/* СТРОКА ПОИСКА */
.inputSearchContainer {
display: inline-flex;
width: 536px;
max-width: 536px;
margin: 0 29px 0 20px;
border: none;
z-index: 4;
}


.searchInput {
display: inline-block;
width: 100%;
height: 64px;
color: #333;
border-radius: 8px;
border: none;
outline: none;
transition: background .3s;
background-color: #f5f5f5;
padding-left: 25px;
box-sizing: border-box;
z-index: 4;
}
.searchInput:focus, .searchInput:hover {
box-shadow: 6px 6px 6px 8px rgba(89,16,0,.08);
background-color: #fff;
z-index: 4;
}

.iconSearchContainer {
display: flex;
position: relative;
left: -3vw;
top: 1.3vh;
background: url(../assets/image/icon-magnifier.png) no-repeat center / 24px 24px;
min-width: 40px;
height: 40px;
border: none;
z-index: 3;
}

.iconSearchContainer:hover, .iconSearchContainer:focus {
background-color: #f5f5f5;
box-shadow: 0 6px 8px rgba(89,16,0,.08);
z-index: 2;
}

/* Конец INPUT */

/* Начало кнопок HeaderBot */

.buttonContainer {
display: inline-flex;
background-color: inherit;
width: 320px;
border: none;
}

.buttonHeaderBotContainer {
display: inline-flex;
flex-direction: column;
justify-content: center;
align-items: center;
background: inherit;
font-size: 14px;
line-height: 18px;
width: 90px;
height: 7vh;
color: #4e4e4e;
border: none;
}

.buttonHeaderBotContainer:hover {
color: #4e4e4e;
}

.iconButtonBottomHeader {
display: flex;
flex-direction: column;
background-size: contain;
background-repeat: no-repeat;
background-position: center;
min-width: 25px;
height: 25px;
border: none;
}
.textButtonBottomHeader {
display: flex;
flex-direction: column;
}
#comparisonIcon {
background-image: url('../assets/image/icon-circular-pie-graph.png');
}

#iconHeart {
background-image: url('../assets/image/icon-heart.png');
}

#iconShoppingCart {
background-image: url('../assets/image/icon-shopping-cart.png');
}

#iconEntrance {
background-image: url('../assets/image/icon-register.png');
}
</style>

<script>
/*
Vue.createApp({
  methods: {
    onfocus(event) {
      document.querySelector('html').style.backgroundColor = orange;
    },
  },
}); */
</script>
