<template>

  <HeaderMain/>
  <AdvantageCard/>
  <History/>
  <Reservation/>
  <DishesCard/>
  <MenuCard/>
  <ReviewsSlider/>
  <GalleryCard/>
  <Cooks/>
  <LastCard/>

</template>

<script>
import HeaderMain from './components/Header.vue'
import AdvantageCard from './components/Card.vue'
import History from './components/History.vue'
import Reservation from './components/Reservation.vue'
import DishesCard from './components/Dishes.vue'
import MenuCard from './components/MenuCard.vue'
import ReviewsSlider from './components/ReviewsSlider.vue'
import GalleryCard from './components/Gallery.vue'
import Cooks from './components/Cooks.vue'
import LastCard from './components/LastCard.vue'



export default {
  name: 'App',
  components: {
    HeaderMain,
    AdvantageCard,
    History,
    Reservation,
    DishesCard,
    MenuCard,
    ReviewsSlider,
    GalleryCard,
    Cooks,
    LastCard
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
