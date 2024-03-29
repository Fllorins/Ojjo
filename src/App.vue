<script setup>
import HeaderMy from './components/HeaderMy.vue'
import FooterMy from './components/FooterMy.vue'
import FormMail from './components/FormMail.vue'
</script>

<template>
  <div class="wrapper">
    <div class="firstscreen">
      <!-- <div class="firstscreen-"></div> -->

      <HeaderMy />

      <section class="firstscreen-section">
        <div class="firstscreen-section-container">
          <div class="firstscreen-info container">
            <h1 class="firstscreen-info__title">Долго, дорого, богато!</h1>
            <div class="firstscreen-info__btn">
              <a class="firstscreen-info__link" href="#">каталог изделий </a>
            </div>
          </div>
          <div class="block"></div>
          <div class="container">
            <div class="etikets">
              <div class="etiket">
                <img src="/etiket.png" alt="etiket" />
              </div>
              <div class="etiket-border"></div>
              <div class="etiket">
                <img src="/etiket.png" alt="etiket" />
              </div>
              <div class="etiket">
                <img src="/etiket.png" alt="etiket" />
              </div>
              <div class="etiket">
                <img src="/etiket.png" alt="etiket" />
              </div>
              <div class="etiket">
                <img src="/etiket.png" alt="etiket" />
              </div>
              <div class="etiket">
                <img src="/etiket.png" alt="etiket" />
              </div>
            </div>
          </div>
        </div>
      </section>
    </div>
  </div>

  <main>
    <FormMail />
  </main>
  <FooterMy />
</template>

<style lang="scss" scoped>
@import '../src/assets/styles/variables.scss';
.firstscreen {
  display: inline-block;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  height: 100vh;
  width: 100vw;

  background-image: url('/firstscreen.jpg');
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  margin-bottom: 50px;
}

/* firstscreen */
.firstscreen-section {
  height: 80vh;
  display: flex;
  justify-content: flex-end;
  margin-top: 50px;
}
.firstscreen-section-container {
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
}
.firstscreen-info__title {
  margin-bottom: 50px;
  font-family: 'Nato Serif Bold';
  font-weight: 700;
  font-size: 36px;
  text-align: center;
}
.firstscreen-info__btn {
  margin-bottom: 90px;
}
.firstscreen-info__link {
  padding: 15px 35px;
  border: 1px solid #fff;
  font-size: 18px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  text-align: center;
  transition: all 0.8s ease;
  &:hover {
    color: $color-second;
    background: $color-white;
    border: 1px solid $color-second;
  }
}

.etikets {
  margin-top: 30px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.etiket:not(:last-child) {
  border-right: 1px solid #fff;
}
.block {
  width: 100vw;
  height: 1px;
  background: $color-white;
}
</style>
