<template>
  <div class="">
    <nav class="navbar navbar-light row">
      <div class="col"></div>
  <a class="col navbar-brand" href="#"><p>Balzac</p></a>
  <button class="col navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
  </div>
</nav>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.navbar-brand{
  padding-left: 40px;
}

navbar {
  text-align: center;
}

button.navbar-toggler{
  border: none;
}
</style>
