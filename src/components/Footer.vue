<template>
  <div>
    <div class="footer-content">
      <div class="left-part">
        <div class="phone">
          <div>
            <span>+7 (423) 280-98-70</span>
          </div>
          <div>
            <span>+ 7 967 958 9870</span>
          </div>
        </div>
        <div class="email">
          <div class="email-content">
            info@neurolab.ru
          </div>
          <div class="email-message">
            Написать нам
          </div>
        </div>
        <div class="address">
          <span>г.Гомель, ул. Тельмана 24</span>
        </div>
        <div class="info">
          <div class="info-content">
            <span>
            <strong>ПОДПИШИТЕСЬ</strong> на еженедельный
            дайджест экономики и бизнеса для предпренимателей.
          </span>
          </div>
          <div class="info-input">
            <div>
              <b-form-input list="my-list-id" placeholder="Электронная почта"/>
              <datalist id="my-list-id"/>
            </div>
            <div class="btn">
              <b-button variant="light">Подписаться</b-button>
            </div>
          </div>
          <div class="info-content last">
            <span>Мы используем сервис MailChimp для рассылки.
            Нажимая кнопку «Подписаться», вы соглашаетесь на обработку персональных данных
            и с условиями политики конфиденциальности.</span>
          </div>
        </div>
      </div>

      <div class="right-part">
        <div class="links">
          <div>
            О компании
          </div>
          <div>
            Финансовые услуги
          </div>
          <div>
            Новости
          </div>
          <div>
            Вопрос-ответ
          </div>
          <div>
            Документы
          </div>
          <div>
            Контакты
          </div>
          <div>
            Противодействие коррупции
          </div>
          <div>
            Карта сайта
          </div>
        </div>
        <div class="images">
          <div>
            <div class="img">
              <img src="../assets/logo.png" width="20" height="20" alt="">
            </div>
            <div class="img-content">
              Микрокредитная компания Приморского края
            </div>
          </div>
          <div>
            <div class="img">
              <img src="../assets/logo.png" width="20" height="20" alt="">
            </div>
            <div class="img-content">
              Учредитель компании Администрация Приморского края
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
name: "Footer"
}
</script>

<style scoped>
 .footer-content{
   display: flex;
   flex-direction: row;
   flex-wrap: wrap;
   background-color: black;
 }
 .left-part{
   width: 60vw;
   background-color: rgb(52, 58, 64);
 }
 .right-part{
   width: 40vw;
  background-color: rgb(28, 31, 38);
 }
  .phone{
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    color: lightgray;
    font-size: 1.5rem;
    margin-left: 40rem;
    margin-right: 2rem;
    margin-top: 5rem;
  }
  .email{
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    color: lightgray;
    font-size: 1.5rem;
    align-items: center;
    margin-left: 40rem;
    margin-right: 2rem;
    margin-top: 2rem;
  }
  .email-message{
    font-size: 1rem;
    margin-left: 3rem;
    text-decoration-line: underline;
  }
  .address{
    display: flex;
    flex-wrap: wrap;
    color: lightgray;
    font-size: 1.5rem;
    margin-left: 40rem;
    margin-right: 2rem;
    margin-top: 2rem;
  }
  .info{
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    font-size: .7rem;
    color: lightgray;
    margin-left: 40rem;
    margin-right: 2rem;
    margin-top: 2rem;
  }
  .info-input{
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    margin-top: 1rem;
    margin-bottom: 1rem;
  }
  .last{
    margin-bottom: 3rem;
  }

  .right-part{
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
  }
  .links{
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    color: lightgray;
    font-size: 1rem;
    margin-top: 5rem;
    margin-left: 2rem;
  }
  .links > div{
    margin: .5rem 0 .5rem 0;
  }
  .links > div:hover{
    color: #fff;
    transition: .4s;
    cursor: pointer;
  }
  .images{
    margin-top: 5rem;
  }
  .images > div {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    align-items: center;
  }
  .img-content{
    color: lightgray;
    font-size: .8rem;
    margin-left: 2rem;
  }
  .img-content:hover{
    color: #fff;
    transition: .4s;
    cursor: pointer;
  }
</style>