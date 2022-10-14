<template>
  <div class="card-menu">
    <div class="card-menu__recomended" v-if="showRecom">
      RECOMMENDED
    </div>
    <div class="card-menu__illustration">
      <img src="../assets/menuItem.svg" class="card-menu__img">
      <div class="card-menu__price">
        420
      </div>
    </div>
    <div class="card-menu__title">
      Гамбургер макси
    </div>
    <div class="card-menu__description">
      Максимально толстый<br>слой мяса
    </div>
    <div class="card-menu__button-position">
      <div class="card-menu__button">
        ЗАКАЗАТЬ
      </div>
    </div>



  </div>
</template>


<script>
export default {
  name: 'MenuItemCard',
  props: {
    showRecom: Boolean
  }
  
}
</script>