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
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d180376.82169436332!2d38.83286421003475!3d45.057642982401596!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x40f04564714535b3%3A0xf720794f56c4beb6!2z0JrRgNCw0YHQvdC-0LTQsNGALCDQmtGA0LDRgdC90L7QtNCw0YDRgdC60LjQuSDQutGA0LDQuQ!5e0!3m2!1sru!2sru!4v1686391582461!5m2!1sru!2sru" width="806" height="199" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
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
  .container{
  width:1440px;
  padding-left:114px;
  padding-right:95px;
  font-family: 'Inter';
  font-style: normal;
  }
  .wrapp{
  display:flex;
  flex-direction:row;
  }
  .left{
    margin-right:57px;
  }
  .left__block{
    margin-bottom: 18px;
  }
  .left__title{
    font-size: 14px; 
    margin-bottom:11px;
    font-family: 'Inter';
    }
  .left__sel{
    border: 1px solid #9DA3AE; 
    border-radius: 5px;
    padding:10px
  }
  .flex{
    display: flex;
  }
  .left__wrappchkbx{
   margin-right:40px;
  }
  .left__chkbxtitle{
    margin-bottom: 11px;
    font-family: 'Inter';
  }
  .price{
    font-size: 14px;
    margin-bottom:11px;
    font-family: 'Inter';
  }
  .price__wrapp{
  display:flex;
  margin-bottom:18px;
  }
  .price__inp{
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  padding: 9px 12px;
  gap: 10px;width: 127px;
  height: 35px;
  border: 1px solid #9DA3AE;
  border-radius: 5px;
  margin-right: 10px;
  }
  .change{
    font-size: 14px; 
    margin-bottom:11px;
    font-family: 'Inter';
  }
  .change__sell{
  border: 1px solid #9DA3AE; 
  border-radius: 5px;
  padding:10px;
  margin-bottom:18px;
  }
  .change__btnm{
  text-align:center;
  }
  .change__btn{
  background: #EC5340;
  border-radius: 5px;
  width: 349px;
  height: 40px;
  color:white;
  }
  .title{
    font-size: 29px;
    line-height: 35px;
    margin-bottom:18px;
    font-weight: bold;
    font-family: 'Inter';
  }
  body{
   font-family: 'Inter'!important;
  }
  .mainbtn{
  display: flex;
  justify-content: center;
  width:806px;
  font-family: 'Inter';
  font-style: normal;
  font-weight: 500;
  font-size: 15px;
  line-height: 18px;
  background-color:white;
  padding:9px, 351px, 9px, 351px;
  margin-top:28.5px;
  cursor:pointer;
  margin-bottom:59px;
  }
  .sell{
    margin-bottom:23px;
    width: 197px;
    height: 36px;
    border: 1px solid #9DA3AE;
    border-radius: 5px;
    padding:10px;
  }
  .card{
    width:214px;
  }
  .card__paint{
  width:214px;
  height:214px;
  }
  .card__title{
  margin-bottom:5px;
  font-weight:700;
  }
  a{
    text-decoration: none;
    color: black;
  }
</style>
