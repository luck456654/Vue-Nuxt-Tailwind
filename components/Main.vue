<template>
  <div>
   <div className="container">
     <div style="display:flex;flex-direction:row">
        <div class="left">
          <div class="left__block">
          <div class="left__title">Город</div>
          <select class="left__sel">
            <option>Выберите Город</option>
            </select>
          </div>
          <div class="left__block">
          <div class="left__title">Округ</div>
          <select class="left__sel">
            <option>Выберите Округ</option>
          </select>
          </div>
          <div class="left__block">
          <div class="left__title">Район</div>
          <select class="left__sel">
            <option>Выберите Район</option>
            </select>
          </div>
          <div class="left__title">К-во комнат</div>
        <div class="flex">
          <div class="left__wrappchkbx">
            <input type="checkbox" class="left__chkbxtitle">1 комнатная</input><br>
            <input type="checkbox" class="left__chkbxtitle">3 комнатная</input><br>
            <input type="checkbox" class="left__chkbxtitle">Студия</input><br>
          </div>
          <div>
            <input type="checkbox" class="left__chkbxtitle">2 комнатная</input><br>
            <input type="checkbox" class="left__chkbxtitle">4 комнатная</input>
          </div>
          </div>
          <div class="price">Cтоимость</div>
          <div class="price__wrapp">
          <input type="text" placeholder="0" class="price__inp">
          <input type="text" placeholder="30 234 234" class="price__inp">
          </div>
          <div class="change">Cрок сдачи</div>
          <select class="change__sell">
            <option>Выберите срок сдачи</option>
            </select><br>
            <div class="change__btnm">
          <button class="change__btn">Показать 287 объект</button>
            </div>
        </div>
        <div>
        <div class="title">
          Подбор новостройки в Краснодаре 287
        </div>
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d180376.82169436332!2d38.83286421003475!3d45.057642982401596!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x40f04564714535b3%3A0xf720794f56c4beb6!2z0JrRgNCw0YHQvdC-0LTQsNGALCDQmtGA0LDRgdC90L7QtNCw0YDRgdC60LjQuSDQutGA0LDQuQ!5e0!3m2!1sru!2sru!4v1686391582461!5m2!1sru!2sru" width="100%" height="199" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        <button class="mainbtn">
          
          Смотреть на карте
          </button>
        <br>
        <select class="sell">
          <option>Cначала дешевые</option>
        </select>
        <a href="/second">
        <div class="card">
          <img src="card.png" class="card__paint">
          <div class="card__title">ЖК Патрики</div>
          <div class="card__title">от 7 457 100 ₽</div>
          <div>ул. Старокубанская / ул. Селезнева ХБК</div>
        </div>
        </a>  
     </div>
     </div>
   </div>
  </div>
</template>
<script src="https://cdn.tailwindcss.com"></script>
<script>

export default {
  


  

  data() {
    return {
     
    };
  },
  
  
  

};
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
  @apply w-[1440px] not-italic pl-[114px] pr-[95px];
  font-family: "Inter";
}
.wrapp {
  @apply flex flex-row;
}
.left {
  @apply mr-[57px];
}
.left__block {
  @apply mb-[18px];
}
.left__title {
  @apply text-sm mb-[11px];
  font-family: "Inter";
}
.left__sel {
  @apply border p-2.5 rounded-[5px] border-solid border-[#9DA3AE];
}
.left__wrappchkbx {
  @apply mr-10;
}
.left__chkbxtitle {
  @apply mb-[11px];
  font-family: "Inter";
}
.price {
  @apply text-sm mb-[11px];
  font-family: "Inter";
}
.price__wrapp {
  @apply flex mb-[18px];
}
.price__inp {
  @apply flex flex-row items-start gap-2.5 w-[127px] h-[35px] border mr-2.5 px-3 py-[9px] rounded-[5px] border-solid border-[#9DA3AE];
}
.change {
  @apply text-sm mb-[11px];
  font-family: "Inter";
}
.change__sell {
  @apply border mb-[18px] p-2.5 rounded-[5px] border-solid border-[#9DA3AE];
}
.change__btnm {
  @apply text-center;
}
.change__btn {
  @apply w-[349px] h-10 text-[white] rounded-[5px];
  background: #ec5340;
}
.title {
  @apply text-[29px] leading-[35px] font-[bold] mb-[18px];
  font-family: "Inter";
}
body {
  font-family: "Inter" !important;
}
.mainbtn {
  font-family: "Inter";
  border: 1px solid;
  width: 100%;
  margin-bottom: 18px;
  margin-top: 18px;
}
.sell {
  @apply w-[197px] h-9 border mb-[23px] p-2.5 rounded-[5px] border-solid border-[#9DA3AE];
}
.card {
  @apply w-[214px];
}
.card__paint {
  @apply w-[214px] h-[214px];
}
.card__title {
  @apply font-bold mb-[5px];
}

</style>
