<template>
<div class="headerBotContainer">
    <div class="containerHeaderBottomLogoCatalog">
        <a class="containerLogoHeaderBottom">
            <div id="headerLogo">
            </div>
        </a>
            <div class="menuCatalogButton">
                <span class="headerBottomCatalogTittle">Каталог</span>
                    <svg class="headerBottomArrowSvg" width="24px" height="24px" fill="none" view-box="0 0 24 24">
                    <path d="M16.594 8.578L18 9.984L12 15.984L6 9.984L7.406
                 8.578L12 13.172L16.594 8.578Z" fill="#fff"></path></svg>
            </div>
    </div>
<div class="inputSearchContainer">
    <input class="searchInput" placeholder="Поиск по сайту" type="search"
      onfocus="document.querySelector('html').style.backgroundColor = '#d5d5d5';"
      onblur="document.querySelector('html').style.backgroundColor = '#fff';">
        <button class="iconSearchContainer">
        </button>
</div>
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
</template>

<style>
.headerBotContainer {
margin: 2vh 0 2vh 0;
width: 100%;
height: 10vh;
align-items: center;
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
}

.containerLogoHeaderBottom  {
    height: 64px;
    display: flex;
    width: 50%;
    padding-left: 20px;
    padding-right: 20px;
    align-items: center;
    border-top-left-radius: 12px;
    border-bottom-left-radius: 12px;
    transition: .2s;
    cursor: pointer;
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
}

.headerBottomArrowSvg {
    transition: all 200ms ease-out 0ms;
}

/* СТРОКА ПОИСКА */

.searchInput {
display: flex;
flex-direction: row;
height: 7vh;
min-width: 27.5vw;
color: #333;
border-radius: 12px;
border: none;
outline: none;
transition: background .3s;
background-color: #f5f5f5;
padding-left: 25px;
}
.searchInput:focus, .searchInput:hover {
box-shadow: 0 6px 8px rgba(89,16,0,.08);
background-color: #fff;
}

.inputSearchContainer {
display: inline-flex;
flex-direction: row;
max-width: 27.5vw;
margin-left: 1vw;
}

.iconSearchContainer {
display: flex;
position: relative;
left: -3vw;
top: 1.3vh;
justify-content: end;
align-items: end;
background: url(../assets/image/icon-magnifier.png) no-repeat center / 24px 24px;
min-width: 40px;
height: 40px;
border: none;
border-radius: 5px;
}

.iconSearchContainer:hover, .iconSearchContainer:focus {
background-color: #f5f5f5;
box-shadow: 0 6px 8px rgba(89,16,0,.08);
}

/* Конец INPUT */

/* Начало кнопок HeaderBot */

.buttonHeaderBotContainer {
display: inline-flex;
flex-direction: column;
justify-content: center;
align-items: center;
border: none;
background: #fff;
font-size: 14px;
line-height: 18px;
min-width: 5vw;
height: 7vh;
color: #4e4e4e;
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

</script>
