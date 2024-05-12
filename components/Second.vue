<template>
  <div>
  <div class="container">
  <div class="title">ЖК Патрики</div>
  <div class="wrapper">
  <div class="left">
    <img class="mainimg" src="secmainimg.png">
    <div class="title desk">О Жилом комплексе</div>
    <div class="block">
        <div class="block__left">
            <div class="block__wrapp"><div class="block__capt">Адрес объекта:</div><div class="block__capt">ул. Старокубанская / ул. Селезнева</div></div>
             <div class="block__wrapp"><div class="block__capt">Срок сдачи:</div><div class="block__capt">2025</div></div>
             <div class="block__wrapp"><div class="block__capt">Город:</div><div class="block__capt">Краснодар</div></div>
             <div class="block__wrapp"><div class="block__capt">Район:</div><div class="block__capt">С ремонтом</div></div>
             <div class="block__wrapp"><div class="block__capt">Отделка:</div><div class="block__capt"></div></div>
        </div>
        <div class="block__right">
             <div class="block__wrapp"><div class="block__capt">Этажность:</div><div class="block__capt">6-18 этажей</div></div>
             <div class="block__wrapp"><div class="block__capt">Материал ЖК:</div><div class="block__capt">Монолит-Кирпич</div></div>
             <div class="block__wrapp"><div class="block__capt">Округ:</div><div class="block__capt">Карасунский</div></div>
             <div class="block__wrapp"><div class="block__capt">Класс жилья:</div><div class="block__capt">Бизнес</div></div>
             <div class="block__wrapp"><div class="block__capt">Территория:</div><div class="block__capt">Закрытая</div></div>
        </div>
        
    </div>
    <div class="title desk">Описание</div>
    <div class="capt">
    Жилой комплекс «Патрики». Новый проект. Новый формат. Новая архитектура. ЖК «Патрики» расположен на пересечении улиц Селезнева и Старокубанская на месте заброшенного завода «Краснодарсельмаш». Новый жилой район включает в себя полноценную инфраструктуру - жилые дома с современной архитектурой и оригинальным дизайном вечерней подсветки, школа, детские сады, прогулочные скверы, зоны отдыха и игровые площадки. Удачная локация комплекса подарит жителям массу преимуществ. В нескольких минутах ходьбы торговый центр СБС и Леруа Мерлен, супермаркет Ашан, семейный магнит, учебные и медицинские учреждения. Тут каждая деталь создана для комфорта жителей и отвечает современным стандартам комплексного строительства.    
    </div>    
  <div class="more">Читать далее</div>
  <div class="whatsaap">
    <img src="wts.png" class="whatsaap__img"/>
    <div class="whatsaap__text">
        <div class="whatsaap__desk">Презентация на WhatsApp</div>
        <div class="whatsaap__desk">Скачайте презентацию на WhatsApp</div>
    </div>    
  </div>
  <div class="title desk var">Варианты планировок в ЖК Патрики  343</div>
  <div class="more var__desk">Выберите количество комнат</div>
  <div class="var__wrapp">
  <div class="var__sell">
     1 ком
  </div>
  <div class="var__sell">
     2 ком
  </div>
  <div class="var__sell">
     3 ком
  </div>
  <div class="var__sell">
     Cтудия
  </div>
  </div>
<div class="var__card">
    <img class="var__img" src="kom.png">
    <div class="var__desk">1 комнатная</div>
    <div class="var__desk">43.19 м2</div>
</div>
<button class="mainbtn">Показать еще</button>
<div class="title desk">Расположение ЖК Патрики</div>
<div class="more mgb">Краснодар, Карасунский, ХБК, ул. Старокубанская / ул. Селезнева</div>
<div class="more mb">До центра, 15 мин</div>
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d180376.82169436332!2d38.83286421003475!3d45.057642982401596!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x40f04564714535b3%3A0xf720794f56c4beb6!2z0JrRgNCw0YHQvdC-0LTQsNGALCDQmtGA0LDRgdC90L7QtNCw0YDRgdC60LjQuSDQutGA0LDQuQ!5e0!3m2!1sru!2sru!4v1686391582461!5m2!1sru!2sru" width="100%" height="288" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
  </div>
  <div class="right">
    <div class="right__container">
        <div class="right__wrapper">
        <img src="tochno.png" class="right__img">
        <div class="right__right">
            <div class="right__title">Застройщик</div>
            <div class="right__desk">ГК ТОЧНО</div>
        </div> 
        </div>
        <div class="right__text">Связаться с отделом продаж</div>
        <div class="right__text">8 918 620 12 35</div> 
        <hr>
        <div class="right__text">или оставьте ваш номер, и мы вам перезвоним</div> 
        <input type="text" class="right__tell" placeholder="+7 ___ ___ _____">   
        <button class="right__btn">Перезвоните мне</button>
        
    </div>
  </div>
  </div>
  </div>   
  </div>
</template>

<script>
export default {
  name: 'Second'
}
</script>

<style scoped>
@font-face {
  font-family: "Inter";
  font-style: normal;
  font-weight: 900;
  src: local("InterRegular.ttf"),
    url("~/components/fonts/InterRegular.woff") format("woff");
}
.container {
  @apply w-[1440px] w-[1440px] not-italic mt-[52px] mx-auto pb-[76px];
  font-family: "Inter";
  }
.left {
  @apply mr-[41px];
}
.title {
  @apply not-italic font-bold text-[29px];
  font-family: "Inter";
}
.wrapper {
  @apply flex w-[906px] h-[622px];
}
.mainimg {
  @apply mb-[105px];
}
.desk {
  @apply mb-[19px];
}
.block {
  @apply flex text-sm;
}
.block__wrapp {
  @apply flex mb-2.5;
}
.block__left {
  @apply mr-3.5;
}
.capt {
  @apply not-italic font-normal text-sm mb-2.5;
  font-family: "Inter";
}
.more {
  @apply text-sm;
}
.whatsaap {
  @apply w-full h-[74px] bg-[#5EC069] flex flex-row items-center text-[white] mb-[46px];
}
.whatsaap__img {
  @apply w-10 h-10 ml-6 mr-4;
}
.var {
  @apply mb-[35px];
}
.var__desk {
  @apply mb-[19px] mb-2.5 pl-2.5;
}
.var__sell {
  @apply w-[83px] h-[49px] flex justify-between items-center mr-[5px] pl-2.5 border-2 border-solid hover:bg-[#9DA3AE] hover:text-[white];
}
.var__wrapp {
  @apply flex mb-[18px];
}
.var__card {
  @apply w-[214px] h-[273px] border mb-[18px] border-solid border-[gray];
}
.var__img {
  @apply w-[214px] h-[214px];
}
.mainbtn {
  @apply w-full flex flex-row justify-center h-[50px] bg-[white] text-base mb-[45px] pt-5 border-2 border-solid border-[#9DA3AE];
}
.mgb {
  @apply mb-[9px];
}
.mb {
  @apply mb-[25px];
}
.right__container {
  @apply w-[302px] h-[348px] border p-7 border-solid border-[#9DA3AE];
}
.right__wrapper {
  @apply flex;
}
.right__img {
  @apply w-[66px] h-[38px] mr-[13px];
}
.right__desk {
  @apply font-bold mb-[22px];
}
.right__text {
  @apply not-italic font-medium text-sm mb-[13px];
  font-family: "Inter";
}
.right__tell {
  @apply flex flex-row items-center w-[93%] h-10 border mb-[13px] px-3 py-[9px] rounded-[5px] border-solid border-[#9DA3AE];
}
.right__btn {
  @apply flex flex-row justify-center items-center w-[102%] h-10 text-[white] border px-3 py-[9px] rounded-[5px] border-solid border-[#5EC069];
  background: #5ec069;
}

  </style>