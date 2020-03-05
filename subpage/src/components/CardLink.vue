<template>
<div class="container">
<div class="card mb-3 shadow p-3 mb-5 bg-white rounded" >
  <div class="row no-gutters">
    <div class="col-md-4">
      <slot></slot>
    </div>
    <div class="col-md-8">
      <div class="card-body">
        <h5 class="card-title">{{cardTitle}}</h5>
        <p class="card-text">{{cardText}}</p>
        <p class="card-text"><strong class="text-muted">{{cardLink}}</strong></p>
      </div>
    </div>
  </div>
</div>


</div>

</template>

<script>


export default {
  name: 'CardLink',
  props: {
    cardTitle: String,
    cardText: String,
    cardLink: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css?family=Poppins:400,700&display=swap');


.container {
    width: 100%;
    padding: 0;
    
}
.img{
  width: 100%;
}
.card {
    width: 100%;
    padding: 0;
}

.card-text {
  opacity: 0.56;
  color: #111113;
  font-family: 'Poppins';
  font-size: 15px;
  letter-spacing: 0.2px;
  line-height: 20px;
  text-align: left;
  
}

.card-title{
    color: #111113;
  font-family: 'Poppins';
  font-size: 20px;
  font-weight: bold;
  letter-spacing: 0.4px;
  line-height: 20px;
  text-align: left;
}



.text-muted{
  color: #111113;
  opacity: 1;
}

@media (min-width: 1120px){

    h5 {
        color: #111113;
        font-family: Poppins;
        font-size: 16px;
        font-weight: bold;
        letter-spacing: 0.25px;
        line-height: 20px;
        text-align: center;
        align-self: center;
    }

    p {
  opacity: 0.56;
  color: #111113;
  font-family: Poppins;
  font-size: 13px;
  letter-spacing: 0.2px;
  line-height: 20px;
  text-align: center;
  align-self: center;
}

    .container {
    width: 70%;
}
}
</style>
