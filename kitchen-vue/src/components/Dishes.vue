<template>
    <div class="dishes">
        <div class="container container_position">
            <div class="dishes__title">
                Наши<span class="dishes__title_brown"> Блюда</span>
            </div>
            <div class="dishes__menu">
                    <img src="../assets/dishesImgBig.svg" class="dishes__img_main">
                    <div class="dishes__price">
                        <div class="dishes__item">
                            <img src="../assets/dishesImgMini.svg" class="dishes__img_mini">
                            <div class="dishes__name">
                                Гамбургер&nbsp;мини
                            </div>
                            <div class="dishes__ellipsis"></div>
                            <div class="dishes__value">
                                220&nbsp;₽
                            </div>
                        </div>
                        <div class="dishes__item">
                            <img src="../assets/dishesImgMini.svg" class="dishes__img_mini">
                            <div class="dishes__name">
                                Гамбургер&nbsp;мини
                            </div>
                            <div class="dishes__ellipsis"></div>
                            <div class="dishes__value">
                                220&nbsp;₽
                            </div>
                        </div>
                        <div class="dishes__item">
                            <img src="../assets/dishesImgMini.svg" class="dishes__img_mini">
                            <div class="dishes__name">
                                Гамбургер&nbsp;мини
                            </div>
                            <div class="dishes__ellipsis"></div>
                            <div class="dishes__value">
                                220&nbsp;₽
                            </div>
                        </div>
                    </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'DishesCard',
    props: {
        msg: String
    }
}
</script>