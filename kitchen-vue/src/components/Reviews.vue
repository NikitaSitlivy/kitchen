<template>
    <div class="review">
        <div class="review__text">
           {{visitor.text}}
        </div>
        <img src="../assets/visitor.svg" class="review__img">
        <div class="review__visitor">
            {{visitor.statusPerson}}
        </div>
        <div class="review__name">
            {{visitor.name}}
        </div>
        
    </div>
</template>

<script>
export default {
    name: 'ReviewsCard',
    props: {
        visitor: Object
    }
}
</script>