<template>
<div class="container">
<div class="row row-cols-2 row-cols-xl-3">
    <div class="col "><img data-toggle="modal" data-target="#noiseModal" style="cursor: zoom-in" src="../assets/noise.jpg" class="img-fluid " alt="Responsive image"></div>
    <div class="col "><img data-toggle="modal" data-target="#noiseModal" style="cursor: zoom-in" src="../assets/noise.jpg" class="img-fluid " alt="Responsive image"></div>
    <div class="col "><img data-toggle="modal" data-target="#pixelModal" style="cursor: zoom-in" src="../assets/pixel.jpg" class="img-fluid " alt="Responsive image"></div>
    <div class="col "><img data-toggle="modal" data-target="#wallModal" style="cursor: zoom-in" src="../assets/wall.jpg" class="img-fluid " alt="Responsive image"></div>
    <div class="col "><img data-toggle="modal" data-target="#noiseModal" style="cursor: zoom-in" src="../assets/noise.jpg" class="img-fluid " alt="Responsive image"></div>
    <div class="col "><img data-toggle="modal" data-target="#pixelModal" style="cursor: zoom-in" src="../assets/pixel.jpg" class="img-fluid " alt="Responsive image"></div>
    <div class="col "><img data-toggle="modal" data-target="#pixelModal" style="cursor: zoom-in" src="../assets/pixel.jpg" class="img-fluid " alt="Responsive image"></div>
    <div class="col "><img data-toggle="modal" data-target="#noiseModal" style="cursor: zoom-in" src="../assets/noise.jpg" class="img-fluid " alt="Responsive image"></div>
    <div class="col "><img data-toggle="modal" data-target="#wallModal" style="cursor: zoom-in" src="../assets/wall.jpg" class="img-fluid " alt="Responsive image"></div>
  </div>

  <ImageGalleryModal modalId="noiseModal"><img data-toggle="modal"  src="../assets/noise.jpg" class="img-fluid" alt="Responsive image"></ImageGalleryModal>
  <ImageGalleryModal modalId="pixelModal"><img data-toggle="modal"  src="../assets/pixel.jpg" class="img-fluid" alt="Responsive image"></ImageGalleryModal>
  <ImageGalleryModal modalId="wallModal"><img data-toggle="modal"  src="../assets/wall.jpg" class="img-fluid" alt="Responsive image"></ImageGalleryModal>

 
</div> 
</template>

<script>

import ImageGalleryModal from './ImageGalleryModal';

export default {
  name: 'ImageGallery',
  components: {
    ImageGalleryModal
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


.container {
    width: 100%;
}

img{
    max-width: 100%;
    
}

img:hover {opacity: 0.7;}

.col{
    padding: 20px;
}

@media (min-width: 1120px){
    img{
        max-width: 100%;
        
    }

    .container {
    width: 100%;
    padding-left: 80px;
    padding-right: 80px;
    }
}
</style>
