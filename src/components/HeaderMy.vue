<template>
  <header class="header">
    <div class="container header__container">
      <nav class="nav">
        <ul class="menu__list">
          <li class="menu__item">
            <a href="#" class="menu__link">Контрагентам</a>
          </li>
          <li class="menu__item">
            <a href="#" class="menu__link">Дизайнерам</a>
          </li>
          <li class="menu__item">
            <a href="#" class="menu__link">Вакансии</a>
          </li>
        </ul>
      </nav>

      <div class="logo">
        <a href="#" class="logo__link">
          <img src="/logo.png" alt="logo" class="logo__img" />
        </a>
      </div>

      <div class="buttons-user">
        <div class="search">
          <a href="#" class="search__link">
            <div class="search-btn">
              <div class="search-btn__img">
                <img src="/icons/search.svg" alt="search" />
              </div>
              <div class="search-btn__text">Поиск</div>
            </div>
          </a>
        </div>

        <div class="login">
          <a href="#" class="login__link">
            <div class="login-btn">
              <div class="login-btn__text">Вход/Регистрация</div>

              <div class="login-btn__img">
                <img src="/icons/cust_account.svg" alt="login" />
              </div>
            </div>
          </a>
        </div>

        <div class="like">
          <a href="#" class="like__link">
            <img src="/icons/like.svg" alt="" />
          </a>
        </div>
      </div>
    </div>
  </header>
</template>

<style lang="scss" scoped>
.header__container {
  margin-top: 25px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-size: 14px;
}

.menu__list {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 40px;
  margin-right: 40px;
}

.menu__link {
  transition: all 0.8s ease;
  &:hover {
    opacity: 0.5;
  }
}

.buttons-user {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.search {
  margin-right: 40px;
  &__link {
    opacity: 1;
    transition: all 0.8s ease;
    padding: 0 5px;
    &:hover {
      opacity: 0.5;
    }
  }
}

.search-btn {
  display: flex;
  align-content: center;
  &__img {
    margin-right: 13px;
  }
  &__text {
    white-space: nowrap;
  }
}

.login {
  margin-right: 25px;
  &__link {
    transition: all 0.8s ease;
    padding: 0 5px;
    &:hover {
      opacity: 0.5;
    }
  }
}

.login-btn {
  display: flex;
  &__text {
    margin-right: 40px;
  }
}

.like {
  margin-top: 5px;
  &__link {
    display: inline-block;
    transition: all 0.8s ease;
    &:hover {
      opacity: 0.5;
    }
  }
}
</style>
