<template>
  <div class="header">
    <div class="container container_position">
      <div class="header__top">
        <img src="../assets/logo.svg" class="header__logo">
        <div class="header__top-right">
          <div class="header__nav_cart">
            <div class="header__nav">
              <div class="header__nav-item"><a href="#" class="header__nav-item-link">ГЛАВНАЯ</a></div>
              <div class="header__nav-item"><a href="#" class="header__nav-item-link">МЕНЮ</a></div>
              <div class="header__nav-item"><a href="#" class="header__nav-item-link">О НАС</a></div>
              <div class="header__nav-item"><a href="#" class="header__nav-item-link">БРОНЬ</a></div>
            </div>
            <img src="../assets/cart.svg" class="header__cart">
          </div>
          <div class="header__top-corner">
            <div class="header__contacts">
              <div class="header__contacts_top">
                <img src="../assets/phone.svg" class="header__phone">
                <div class="header__number">
                  +999-888-76-54
                </div>
              </div>
              <div class="header__connection">
                Свяжитесь с нами для бронирования
              </div>
            </div>
            <div class="header__button button">
              ЗАКАЗ СТОЛИКА
            </div>
          </div>
        </div>
      </div>
      <div class="header__title">
        <div class="header__title_h2">
          Добро пожаловать в
        </div>
        <div class="header__title_h1">
          Наш ресторан
        </div>
        <div class="header__title_under-line">
          ДОМ ЛУЧШЕЙ ЕДЫ
        </div>
        <div class="header__button button">
          VIEW MENU
        </div>
      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'HeaderMain',
  props: {
    msg: String
  }
}
</script>

