<template>
    <div class="cooks">
        <div class="container">
            <div class="cooks__title">
                Наши<span class="cooks__title_brown"> Повара</span>
            </div>
            <div class="cooks__photo">
                <img src="../assets/cook1.svg" class="cooks__img">
                <img src="../assets/cook2.svg" class="cooks__img">
                <img src="../assets/cook3.svg" class="cooks__img">
            </div>
        </div> 
    </div>
</template>

<script>
export default {
  name: 'CooksCard',
  props: {
    msg: String
  }
}
</script>