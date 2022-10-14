<template>
    <div class="history">
        <div class="container container_position">
            <div class="history__container">
                <div class="history__left">
                    <div class="history__title">Наша
                        <span class="history__title_brown">
                            История
                        </span>
                    </div>

                    <div class="history__description">
                        Как и у любого другого самобытного места, у нас есть своя, особая история. Идея ресторана пришла
                        основателям неожиданно. Во время прогулки по лесу создатель нашего ресторана застрял в сотнях
                        километров
                        от ближайшего населенного пункта. Вдали от цивилизации и связи им пришлось навремя обустровать
                        себе
                        нехитрый быт, добывать и готовить себе еду.
                    </div>

                    <div class="history__assortment">
                        <div class="history__assortment__card">
                            <div class="history__amount">93</div>
                            <div class="history__name">Напитки</div>
                        </div>
                        <div class="history__assortment__card">
                            <div class="history__amount">206</div>
                            <div class="history__name">Еда</div>
                        </div>
                        <div class="history__assortment__card">
                            <div class="history__amount">71</div>
                            <div class="history__name">Закуски</div>
                        </div>

                    </div>

                </div>


                <div class="history__images">
                    <img src="../assets/historyImg1.svg" class="history__img history__img_first">
                    <img src="../assets/historyImg2.svg" class="history__img history__img_second">
                    <img src="../assets/historyImg3.svg" class="history__img history__img_third">
                    <img src="../assets/historyImg4.svg" class="history__img history__img_fourth">
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'History-card',
    props: {
        // msg: String,
    }
}
</script>
