<template>
    <div class="reservation">
        <img src="../assets/reservationBg.svg" class="reservation__background">
        <div class="container container_position">
            <div class="reservation__container">
                <div class="reservation__title">
                    Отпразднуйте в одном из самых лучших ресторанов.
                    <div class="reservation__advertising">
                        Только в этом месяце бизнес-ланч от 250 ₽
                    </div>
                </div>
                <div class="reservation__button button">
                    ЗАКАЗ СТОЛИКА
                </div>

            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'ReservationCard',
    props: {
        // msg: String,
    }
}
</script>
 