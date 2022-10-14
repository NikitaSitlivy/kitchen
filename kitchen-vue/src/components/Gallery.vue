<template>
    <div class="gallery">
      <div class="gallery__red-block"></div>
      <div class="gallery__red-block_right"></div>
        <div class="container container_position">
            <div class="gallery__title">
                Галерея<span class="gallery__title_brown"> Блюд</span>
            </div>
            <div class="gallery__images">
              <img src="../assets/galleryImg1.svg" class="gallery__img">
              <img src="../assets/galleryImg2.svg" class="gallery__img">
              <img src="../assets/galleryImg3.svg" class="gallery__img">
              <img src="../assets/galleryImg2.svg" class="gallery__img">
              <img src="../assets/galleryImg3.svg" class="gallery__img">
              <img src="../assets/galleryImg1.svg" class="gallery__img">
            </div>

        </div>
    </div>


</template>



<script>
export default {
  name: 'GalleryCard',
  props: {
    msg: String
  }
}
</script>
