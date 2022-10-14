<template>
    <div class="card">
        <div class="container container_position">
            <div class="card__advantages">
                <div class="card__advantage">
                    <img src="../assets/pot.svg" class="card__advantage__img">
                    <div class="card__advantage__title">Магическая
                        <span class="card__advantage__title_brown">Атмосфера
                        </span>
                    </div>
                    <div class="card__advantage__description">
                        В нашем заведении царит магическая атмосфера наполненная вкусными ароматами
                    </div>
                </div>
                <div class="card__advantage">
                    <img src="../assets/pot.svg" class="card__advantage__img">
                    <div class="card__advantage__title">Лучшее качество
                        <span class="card__advantage__title_brown">Еды
                        </span>
                    </div>
                    <div class="card__advantage__description">
                        Качество нашей Еды - отменное!
                    </div>
                </div>
                <div class="card__advantage">
                    <img src="../assets/pot.svg" class="card__advantage__img">
                    <div class="card__advantage__title">Недорогая
                        <span class="card__advantage__title_brown">Еда
                        </span>
                    </div>
                    <div class="card__advantage__description">
                        Стоимость нашей Еды зависит только от ее количества. Качество всегда на высоте!
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'AdvantageCard',
    props: {
        msg: String
    }
}
</script>