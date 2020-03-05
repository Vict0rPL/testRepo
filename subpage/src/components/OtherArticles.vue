<template>
<div class="container">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<div class="row ">
    <div v-if="mobileCover" class=" col-xl-4 order-xl-3"><slot name="imgslot"></slot></div>
    <div v-else class="noMobileCover col-xl-4 order-xl-3"><slot name="imgslot"></slot></div>
    <div class=" col-xl-4 order-xl-1"><h2>{{articleTitle}}</h2></div>
    <div class=" col-xl-4 order-xl-2 cls"><p>{{articleDescription}}</p></div>
</div> 
<div class="row bottomArticle">
    <slot name="leftbottom"></slot>
    <slot name="rightbottom"></slot>
    </div>
<hr>

</div>
</template>

<script>
export default {
  name: 'OtherArticles',
  props:{
      articleTitle: String,
      articleDescription: String,
      mobileCover: Boolean

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.noMobileCover{
    display: none;
}

.container {
    width: 100%;
}
.bottomArticle {
    height: 50px;
    
}
img{
    max-width: 100%;
}

.col{
    padding: 20px;
}

.green{
    color:#25BF11;
    margin: 3px;
}

.orange{
    color: #F13A12;
    margin: 3px;
}

.black {
    color:#111113;
    opacity: 1;
    font-family: "Poppins";
  font-size: 16px;
  letter-spacing: 0.2px;
  line-height: 26px;
}

.cls{
        display: none;
    }

h2 {
  color: #111113;
  font-family: Poppins;
  font-size: 20px;
  font-weight: bold;
  letter-spacing: 0.2px;
  line-height: 30px;
  text-align: left;
}

@media (min-width: 1120px){
    img{
        max-width: 100%;
        
    }

    .noMobileCover{
    display: block;
    }
    
    .cls{
        display: inline;
    }

    h2 {
  color: #111113;
  font-family: Poppins;
  font-size: 24px;
  font-weight: bold;
  letter-spacing: 0.2px;
  line-height: 36px;
  text-align: left;
}

p {
  opacity: 0.56;
  color: #111113;
  font-family: "PT Serif";
  font-size: 16px;
  letter-spacing: 0.2px;
  line-height: 26px;
  text-align: left;
}
    .container {
    width: 80%;
    }
}
</style>
