<template>
      <div class="catalogMenu">
        <a class="containerProductCategoryRefs" id="firstContainerProdustCategoryRefs">
           <span class="iconProductCategoryRefs" id="iconHouseHold"></span>
          <span class="textProductCategoryRefs">Бытовая техника</span>
        </a>
        <a class="containerProductCategoryRefs">
          <span class="iconProductCategoryRefs" id="iconHealth"></span>
          <span class="textProductCategory">Красота и здоровье</span>
        </a>
        <a class="containerProductCategoryRefs">
          <span class="iconProductCategoryRefs" id="iconSmartPhones"></span>
          <span class="textProductCategory">Смартфоны и фототехника</span>
        </a>
        <a class="containerProductCategoryRefs">
          <span class="iconProductCategoryRefs" id="iconTVConsole"></span>
          <span class="textProductCategory">ТВ, консоли и аудио</span>
        </a>
        <a class="containerProductCategoryRefs">
          <span class="iconProductCategoryRefs" id="iconPCLaptops"></span>
          <span class="textProductCategory">ПК, ноутбуки и периферия</span>
        </a>
        <a class="containerProductCategoryRefs">
          <span class="iconProductCategoryRefs" id="iconComponentsPC"></span>
          <span class="textProductCategory">Комплектующие для ПК</span>
        </a>
        <a class="containerProductCategoryRefs">
          <span class="iconProductCategoryRefs" id="iconOfficeFurniture"></span>
          <span class="textProductCategory">Офис и мебель</span>
        </a>
        <a class="containerProductCategoryRefs">
          <span class="iconProductCategoryRefs" id="iconNetworkHardware"></span>
          <span class="textProductCategory">Сетевое оборудование</span>
        </a>
        <a class="containerProductCategoryRefs">
          <span class="iconProductCategoryRefs" id="iconRecreation"></span>
          <span class="textProductCategory">Отдых и развлечения</span>
        </a>
        <a class="containerProductCategoryRefs">
          <span class="iconProductCategoryRefs" id="iconToolConstruction"></span>
          <span class="textProductCategory">Инструмент и стройка</span>
        </a>
        <a class="containerProductCategoryRefs">
          <span class="iconProductCategoryRefs" id="iconGardenEquipment"></span>
          <span class="textProductCategory">Садовая техника</span>
        </a>
        <a class="containerProductCategoryRefs">
          <span class="iconProductCategoryRefs" id="iconHomeDecor"></span>
          <span class="textProductCategory">Дом, декор и посуда</span>
        </a>
        <a class="containerProductCategoryRefs">
          <span class="iconProductCategoryRefs" id="iconAutoitems"></span>
          <span class="textProductCategory">Автотовары</span>
        </a>
        <a class="containerProductCategoryRefs">
          <span class="iconProductCategoryRefs" id="iconAccessories"></span>
          <span class="textProductCategory">Аксессуары и услуги</span>
        </a>
        <a class="containerProductCategoryRefs">
          <span class="iconProductCategoryRefs" id="iconSale"></span>
          <span class="textProductCategory">Распродажа</span>
        </a>
        <a class="containerProductCategoryRefs">
            <svg class="iconProductCategoryRefs" width="20" height="21" viewBox="0 0 20 21" fill="none" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M10 1.53968C5.32682 1.53968 1.53846 5.32804 1.53846 10.0012C1.53846 14.6744 5.32682 18.4628 10 18.4628C14.6732 18.4628 18.4615 14.6744 18.4615 10.0012C18.4615 5.32804 14.6732 1.53968 10 1.53968ZM0 10.0012C0 4.47837 4.47715 0.0012207 10 0.0012207C15.5228 0.0012207 20 4.47837 20 10.0012C20 15.5241 15.5228 20.0012 10 20.0012C4.47715 20.0012 0 15.5241 0 10.0012ZM9.99895 5.51602C10.4238 5.51602 10.7682 5.86042 10.7682 6.28525V10.1608C10.7682 10.5857 10.4238 10.9301 9.99895 10.9301C9.57412 10.9301 9.22972 10.5857 9.22972 10.1608V6.28525C9.22972 5.86042 9.57412 5.51602 9.99895 5.51602ZM10.4046 13.0612C10.7663 13.2841 10.8788 13.758 10.6559 14.1196L10.6538 14.123C10.431 14.4847 9.9571 14.5973 9.59542 14.3744C9.23374 14.1515 9.1212 13.6776 9.34407 13.316L9.34616 13.3126C9.56903 12.9509 10.0429 12.8384 10.4046 13.0612Z" fill="url(#paint0_linear_559_7921)"></path><defs><linearGradient id="paint0_linear_559_7921" x1="25.7321" y1="20.0012" x2="25.7321" y2="0.00122084" gradientUnits="userSpaceOnUse"><stop stop-color="#FC8507"></stop><stop offset="1" stop-color="#FFA218"></stop></linearGradient></defs></svg>
          <span class="textProductCategory">Уцененные товары</span>
        </a>
      </div>
</template>

<style>
a:hover {
color: orange;
}
.catalogMenu {
display: flex;
flex-direction: column;
width: 275px;
height: auto;
}
.containerProductCategoryRefs {
    height: 36px;
    margin: 0 -1px;
    font-size: 16px;
    color: #000;
    padding: 0 0 0 12px;
    width: 280px;
    border-left: 2px solid rgba(0,0,0,0);
    cursor: pointer;
    font-family: "PT Sans","Helvetica","Arial",sans-serif;
    line-height: 1.42857;
}
#firstContainerProdustCategoryRefs {
margin-top: 29px;
}

.iconProductCategoryRefs {
    background-position: center center;
    background-repeat: no-repeat;
    background-size: contain;
    display: inline-block;
    height: 20px;
    margin-right: 20px;
    text-align: center;
    vertical-align: middle;
    width: 24px;
}

.textProductCategory {
width: 251px;
height: 24px;
}
#iconHouseHold {
    background-image: url("https://o.dns-shop.ru/original/st1/5d10cc54f37435f6f745d47bc22b45c5/98ebfc11ee69515d19fe8e70903b78ea7cac12b7e5b8fdf0fce368c8d8d08179.svg");
}
#iconHealth {
background-image: url('https://o.dns-shop.ru/original/st1/509e87425fa85a1f2bed3a7f922e402b/247f64f80dbec3f03c6667382b0b75359d7d1abf3b89fdb7d49c119f03857f74.svg');
}
#iconSmartPhones {
    background-image: url("https://o.dns-shop.ru/original/st1/ce7691a00f0aa2ec6076fe5e52731d6b/bd3471d784869986cb36f2d6c0910a2a829a3e168d69be21dffedbca77f87337.svg");
}
#iconTVConsole {
    background-image: url("https://o.dns-shop.ru/original/st4/81bfc614ba456598e3554dbdc2773b4f/265ed645f85c4835d240e4ca643ed5e60065580bf74181c0e8f1d3a18de7e47a.svg") ;
}
#iconPCLaptops {
    background-image: url("https://o.dns-shop.ru/original/st4/d6c1fafdbec6ec320ddda34a242a9c35/a9114dd2379289bcb47115ea9c8969ca3c12501a801bc5e7c51edd8582919777.svg");
}
#iconComponentsPC {
    background-image: url("https://o.dns-shop.ru/original/st1/10c028f0916dde52a05caf1928dca229/fff5fb06867271a627c8ba72dd1bc618cfc054e984c0581dc5c0323ad76cea68.svg") ;
}
#iconOfficeFurniture {
    background-image: url("https://o.dns-shop.ru/original/st4/e132197d2dbc80041f551fb7856d8b14/2ec4296447234c5c24d52218ad6bb84f9aac52f149d72706d667a942a9cb3c35.svg");
}
#iconNetworkHardware {
    background-image: url("https://o.dns-shop.ru/original/st1/b674267b588f44a206c88d6e41ec7bfc/6516864977311b7b8b54b68ccda7cdb711b83c876765b888f6627335cd0b6b0c.svg") ;
}
#iconRecreation {
    background-image: url("https://o.dns-shop.ru/original/st1/d3827c5d01e87e934bfc7c33d37230eb/7fa73d7ea93a09d6f365be9a149861125b8f848aa2c23ff22a3fc192cc4fdf66.svg") ;
}
#iconToolConstruction {
    background-image: url("https://o.dns-shop.ru/original/st4/a3a6a550e6688cb74fcc0bd5134ccea0/dc52467e896861cee509cded74e85a23cc3e94889a7b4c9fc9afbf46ac97d114.svg");
}
#iconGardenEquipment {
    background-image: url("https://o.dns-shop.ru/original/st4/a653655661952c5c4d46205b6d1d113a/af4f931a1435c09c7f39a45b9b816a7d6afce31a11f707da2498d70f4f6a00ae.svg") ;
}
#iconHomeDecor {
    background-image: url("https://o.dns-shop.ru/original/st1/67a80294738d1bd893f14ffb6943daed/d00f7300737f09db266517262be2c988680a12109871501708c38289e2a4951e.svg") ;
}
#iconAutoitems {
    background-image: url("https://o.dns-shop.ru/original/st4/eeb3af85ad54a60eabe179f88803fbbc/913f0af43a6008cff4bbf6430b2aaefad60607f667f11b155b4fb7a7d530e7b6.svg") ;
}
#iconAccessories {
    background-image: url("https://o.dns-shop.ru/original/st4/ebb83a2b9079df64ffb71dcce74afd8d/de511a91f131e759088a721b86f9a500f829efd65776b532900c2566046581b0.svg");
}
#iconSale {
    background-image: url("https://o.dns-shop.ru/original/st1/4f89e07599c1e25b365e75317bd7d539/c72b444431257531d40ae511605d799f93261bd6da1c9effe8004ac5d72a4c69.svg") ;
}
</style>

<script>
</script>
