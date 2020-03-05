<template>
<div class="down">
    
        <span id="smallspanbutton" class="fa s navbar-toggler-icon"></span>
        <br>
        <br>
        <br>
        <a href="#" class="fa fa-facebook"></a>
        <br>
        <a href="#" class="fa fa-twitter"></a>
        <br>
        <a href="#" class="fa fa-linkedin"></a>
        <br>
        <a href="#" class="fa fa-envelope"></a>
        <br>
    
</div> 
</template>

<script>
export default {
  name: 'SideSocial',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.fa {
  padding: 20px;
  font-size: 15px;
  width: 15px;
  text-align: center;
  text-decoration: none;
  margin: 5px 2px;
  box-sizing: content-box;
}

.fa:hover {
    opacity: 0.7;
}

.fa-facebook {

  color: grey;
}

.fa-envelope {

  color: grey;
}

.fa-twitter {

  color: grey;
}

.fa-linkedin {

  color: grey;
}





.fa:hover {
    opacity: 0.7;
}

@media (min-width: 1120px){
   .down{
       margin-top: 1400px;
   }
   #smallspanbutton {
         padding: 15px;
         margin-left: 5px;
   }
}
</style>
