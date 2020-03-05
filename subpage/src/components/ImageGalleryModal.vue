<template>
<div class="modal fade" :id="modalId" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered" role="document" style="width: 100%">
    <div class="modal-content">
      <slot></slot>
    </div>
  </div>
</div>
</template>

<script>

export default {
  name: 'ImageGalleryModal',
  props: {
    modalId: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>



</style>
