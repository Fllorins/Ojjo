<script setup></script>
<template>
  <div class="footer-first-block">
    <div class="container">
      <h3 class="footer-first-head1">Полезные советы и персональный предложения</h3>
      <h2 class="footer-first-head2">Эксклюзивная рассылка</h2>

      <div class="footer-list-form">
        <div class="footer-list">
          <ul class="footer-list__menu">
            <li class="footer-list__item"><span>Личный менеджер</span></li>
            <li class="footer-list__item"><span>Доставка и оформление</span></li>
            <li class="footer-list__item"><span>Индивидуальный дизайн</span></li>
          </ul>
        </div>
        <div class="footer-form">
          <form class="form">
            <input class="form-email" type="email" name="email" placeholder="Ваш e-mail" />

            <input class="form-submit" type="submit" value="отправить" />
          </form>
        </div>
      </div>
    </div>
  </div>
</template>
<style lang="scss" scoped>
@import '../src/assets/styles/variables.scss';

.footer-first-block {
  width: 100vw;
  background: url('/black-fon.jpg') no-repeat;
}
.footer-first-head1 {
  margin-bottom: 15px;
  padding-top: 100px;
  font-size: 21px;
  font-weight: 400;
  line-height: 140%;
  letter-spacing: 0%;
}
.footer-first-head2 {
  margin-bottom: 60px;
  font-size: 30px;
  font-weight: 700;
  line-height: 41px;
  letter-spacing: 0%;
}
.footer-list-form {
  display: flex;
  justify-content: center;
  align-content: center;
  gap: 80px;
  padding-bottom: 120px;
}
.footer-list {
  &__menu {
    text-align: left;
    gap: 15px;
  }
  &__item {
    padding-left: 40px;
    margin-bottom: 15px;
    background: url('/icons/triangle.svg') no-repeat left 5px;
  }
}

.footer-form {
  display: block;
  width: 450px;
  height: 115px;
  padding: 15px;
  border: 1px solid #fff;
}
.form {
  padding: 20px 22px;
  display: flex;
  gap: 15px;
  align-items: center;
  background: #fff;
}
.form-email {
  padding: 20px 15px;
  height: 45px;
  text-transform: uppercase;
  color: rgba(51, 51, 51, 0.5);
  font-size: 14px;
  font-weight: 500;
  line-height: 16px;
  letter-spacing: 10%;
}
.form-submit {
  height: 45px;
  border: 1px solid #fff;
  color: #fff;
  background: rgb(51, 51, 51);
  font-size: 14px;
  font-weight: 500;
  line-height: 16px;
  letter-spacing: 10%;
  padding: 14px 35px;
  cursor: pointer;
  text-transform: uppercase;
  transition: all 0.8s ease;
  &:hover {
    background-color: #fff;
    color: $color-second;
    border: 1px solid black;
  }
}
</style>
