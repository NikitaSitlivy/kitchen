<template>
    <div class="menu">
        <div class="container container_position">
            <div class="menu__title">
                Наше меню
            </div>
            <div class="menu__items">

                <swiper :navigation="true" :modules="modules" class="mySwiper" :slidesPerView="3" :spaceBetween="30">
                    <swiper-slide v-for="(item,index) in count" :key="index">
                     <MenuItemCard :showRecom="item.isRecomend" />
                    </swiper-slide>
                  
                </swiper>

            </div>
        </div>
    </div>
</template>


<script>
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/css";

import "swiper/css/navigation";



// import required modules
import { Navigation } from "swiper";
import MenuItemCard from './MenuItemCard.vue'
import { ref} from 'vue'

export default {
    components: {
        MenuItemCard,
        Swiper,
        SwiperSlide,
    },
    name: 'MenuCard',
    setup() {
        const count=ref([
            { isRecomend:true},
            { isRecomend:false},
            { isRecomend:false},
            { isRecomend:false},
            { isRecomend:false},
            { isRecomend:true},
            { isRecomend:false},

        ]);

        return {
            modules: [Navigation],
            count
        };
    },
}
</script>
    