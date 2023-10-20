<template>
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
</template>

<style>

.containerHeaderBottomLogoCatalog {
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
}

.containerLogoHeaderBottom  {
    height: 64px;
    display: flex;
    width: auto;
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

</style>

<script>
</script>
