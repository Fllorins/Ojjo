<script setup></script>
<template>
  <footer class="footer">
    <div class="footer__container">
      <div class="footer-second-block container">
        <div class="footer-grid">
          <div class="footer-grid-block">
            <div class="footer-grid-head">
              <a href="#" class="footer-grid-head__link">
                <h3 class="footer-grid-head__heading">Полезные ссылки</h3>
              </a>
            </div>
            <div class="footer-grid-block-info block-links">
              <ul class="block-links__menu">
                <li class="block-links__item">
                  <a href="#" class="block-links__link">Доставка</a>
                </li>
                <li class="block-links__item">
                  <a href="#" class="block-links__link">Оплата</a>
                </li>
                <li class="block-links__item">
                  <a href="#" class="block-links__link">Акции</a>
                </li>
                <li class="block-links__item">
                  <a href="#" class="block-links__link">Политика конфиденциальности</a>
                </li>
              </ul>
            </div>
          </div>
          <div class="footer-grid-block">
            <div class="footer-grid-head">
              <a href="#" class="footer-grid-head__link">
                <h3 class="footer-grid-head__heading">оплата</h3>
              </a>
            </div>
            <div class="footer-grid-block-info">
              <p class="block-info__text">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ullamcorper justo, nec,
                pellentesque.
              </p>
              <div class="block-info-pays">
                <div class="block-info-pays__pay">
                  <img src="/visa.png" alt="visa" class="block-info-pays__img" />
                </div>
                <div class="block-info-pays__pay">
                  <img src="/mcard.png" alt="master card" class="block-info-pays__img" />
                </div>
              </div>
            </div>
          </div>
          <div class="footer-grid-block">
            <div class="footer-grid-head">
              <a href="#" class="footer-grid-head__link">
                <h3 class="footer-grid-head__heading">контакты</h3>
              </a>
            </div>
            <div class="footer-grid-block-info block-contacts">
              <ul class="block-contacts__menu">
                <li class="block-contacts__item">
                  <a href="tel:88122345655" class="block-contacts__link block-tel"
                    >8 (812) 234-56-55</a
                  >
                </li>
                <li class="block-contacts__item">
                  <a href="tel:88122345655" class="block-contacts__link block-tel"
                    >8 (812) 234-56-55</a
                  >
                </li>
                <li class="block-contacts__item">
                  <a href="mailto:ojjo@ojjo.ru" class="block-contacts__link block-mail"
                    >ojjo@ojjo.ru</a
                  >
                </li>
              </ul>
            </div>
          </div>
          <div class="footer-grid-block">
            <div class="footer-grid-head">
              <a href="#" class="footer-grid-head__link"
                ><h3 class="footer-grid-head__heading">социальные сети</h3></a
              >
            </div>
            <div class="footer-grid-block-info block-social">
              <p class="block-social__text">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ullamcorper justo, nec,
                pellentesque.
              </p>

              <div class="block-social-links">
                <div class="block-social-link">
                  <a href="#" class="block-social-link__link">
                    <img src="/icons/youtube.svg" alt="youtube" class="link__icon" />
                  </a>
                </div>
                <div class="block-social-link">
                  <div class="block-social-link">
                    <a href="#" class="block-social-link__link">
                      <img src="/icons/vk.svg" alt="vk" class="link__icon" />
                    </a>
                  </div>
                </div>
                <div class="block-social-link">
                  <div class="block-social-link">
                    <a href="#" class="block-social-link__link">
                      <img src="/icons/facebook.svg" alt="facebook" class="link__icon" />
                    </a>
                  </div>
                </div>
                <div class="block-social-link">
                  <div class="block-social-link">
                    <a href="#" class="block-social-link__link">
                      <img src="/icons/telegram.svg" alt="telegram" class="link__icon" />
                    </a>
                  </div>
                </div>
                <div class="block-social-link">
                  <div class="block-social-link">
                    <a href="#" class="block-social-link__link">
                      <img src="/icons/etsy.svg" alt="etsy" class="link__icon" />
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="footer-down">
          <div class="down-text">
            <a href="#" class="down-text__link">(c) 2020 OJJO jewelry</a>
          </div>
          <div class="down-text"><a href="#" class="down-text__link">(c) 2020 OJJO jewelry</a></div>
          <div class="down-text">
            <a href="#" class="down-text__link">Договор публичной офферты</a>
          </div>
          <div class="down-text"><a href="#" class="down-text__link">Контрагентам</a></div>
          <div class="down-text"><a href="#" class="down-text__link">Сделано Fllosik.info</a></div>
        </div>
      </div>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
@import '../src/assets/styles/variables.scss';
@import '../src/assets/styles/fonts.scss';

.footer-second-block {
  color: $color-second;
}

.footer-grid {
  padding-top: 80px;
  padding-bottom: 60px;
  border-bottom: 1px solid $color-second;
  display: flex;
  justify-content: space-between;
  align-content: center;
  gap: 30px;
  text-align: left;
}
.footer-grid-block {
  max-width: 255px;
  width: 100%;
}
.footer-grid-head {
  margin-bottom: 40px;
  padding: 10px 0;
  border-bottom: 1px solid $color-second;
  width: 100%;
  &__heading {
    font-weight: 500;
    text-transform: uppercase;
    white-space: nowrap;
    font-size: 1em;
    letter-spacing: 10%;
  }
}

.footer-grid-block-info {
  font-size: 14px;
}
.block-links {
}
.block-links__menu {
  display: flex;
  flex-direction: column;
  gap: 15px;
}
.block-links__item {
  font-size: 14px;
  white-space: nowrap;
  transition: all 0.5s ease;
  .hover {
    opacity: 0.5;
  }
}
.block-links__link {
  transition: all 0.5s ease;
  &:hover {
    opacity: 0.7;
  }
}
.block-info-pays {
  margin-top: 20px;
  display: flex;
  align-items: center;
  gap: 20px;
}
.block-contacts__item {
  margin-bottom: 15px;
}
.block-contacts__link {
  padding: 0 5px;
  padding-left: 40px;
}
.block-tel {
  background: url('/icons/tel.svg') no-repeat left -2px;
}
.block-mail {
  background: url('/icons/mail.svg') no-repeat left -2px;
}

.block-social-links {
  margin-top: 20px;
  display: flex;
  align-items: center;
  gap: 20px;
}
.block-contacts__link {
  transition: all 0.5s ease;
  &:hover {
    opacity: 0.7;
  }
}
.link__icon {
  transition: all 0.5s ease;
  &:hover {
    opacity: 0.5;
  }
}
.footer-down {
  padding: 20px 0;
  font-size: 14px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 20px;
}
</style>
