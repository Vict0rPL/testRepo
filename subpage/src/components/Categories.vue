<template>
<div class="container">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">


        <div class="float-left col-xl-6 order-xl-1">
        <p class="grey">O CZYM TEN BLOG</p>
        <hr>
        <div class="row">
            <div class="col-6"><p>Wszystkie kategorie</p></div>
            <div class="col-6"><i class="fa fa-square black"></i></div>
        </div>
        <hr>
        <div class="row">
            <div class="col-6"><p>Jak zacząć projektować UI</p></div>
            <div class="col-6"><i class="fa fa-square green"></i></div>
        </div>
        <hr>
        <div class="row">
            <div class="col-6"><p>Podcast “większe logo”</p></div>
            <div class="col-6"><i class="fa fa-square pink"></i></div>
        </div>
        <hr>
        <div class="row">
            <div class="col-6"><p>Design biznesowo</p></div>
            <div class="col-6"><i class="fa fa-square blue"></i></div>
        </div>
        <hr>
        <div class="row">
            <div class="col-6"><p>Ćwiczenia z ostrą amonicją</p></div>
            <div class="col-6"><i class="fa fa-square orange"></i></div>
        </div>
        <hr>
        <div class="row">
            <div class="col-6"><p>Inne kategorie</p></div>
            <div class="col-6"><i class="fa fa-square yellow"></i></div>
        </div>
        <hr>
        <div class="row">
            <div class="col-6"><p>Subskrybuj!</p></div>
            <div class="col-6"><i class="fa fa-envelope-open orange"></i></div>
        </div>
        <hr>
        </div>

        <div class="float-left col-xl-6 order-xl-2">
            <p class="grey">O CZYM TEN BLOG</p>
            <p>O Autorze</p>
            <hr>
            <p>Mój moodboard</p>
            <hr>
            <p>Inny page / subpage</p>
            <hr>
        </div>

        <div class="float-left col-xl-6 order-xl-4">
            <p class="grey">Co robię</p>
            <div class="row">
            <div class="col-6"><p>Behance</p></div>
            <div class="col-6"><i class="fa fa-behance brand blue"></i></div>
        </div>
        <hr>
        <div class="row">
            <div class="col-6"><p>Dribbble</p></div>
            <div class="col-6"><i class="fa fa-dribbble brand pink"></i></div>
        </div>
        <hr>
        <div class="row">
            <div class="col-6"><p>Instagram</p></div>
            <div class="col-6"><i class="fa fa-instagram brand pink"></i></div>
        </div>
        <hr>
        <div class="row">
            <div class="col-6"><p>YouTube</p></div>
            <div class="col-6"><i class="fa fa-youtube brand red"></i></div>
        </div>
        <hr>
        <div class="row">
            <div class="col-6"><p>Twitter</p></div>
            <div class="col-6"><i class="fa fa-twitter brand blue"></i></div>
        </div>
        <hr>
        <div class="row">
            <div class="col-6"><p>Twitch</p></div>
            <div class="col-6"><i class="fa fa-twitch brand violet"></i></div>
        </div>
        <hr>
        <div class="row">
            <div class="col-6"><p>Spotify podcast</p></div>
            <div class="col-6"><i class="fa fa-spotify brand green"></i></div>
        </div>
        </div>

        <div class="float-left signature col-xl-6 order-xl-3">
            <h3>Balzac</h3>
            <p>©balzac.blog 2019</p>
            <p>Personal blog, personal thoughts.</p>
        </div>
        
 

</div>
</template>

<script>
export default {
  name: 'OtherArticles',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css?family=Poppins:400,600&display=swap');


.brand{
    font-size: 25px;
}

.container {
    width: 100%;

}
.red{
    color:red;
}
.violet{
    color: darkviolet;
}
.green{
    color:#25BF11;
}
.black {
    color: black;
}
.blue{
    color: #2371EF
}
.orange{
    color: #F13A12;
}
.pink{
    color: #DB7CDB;
}
.yellow {
    color: #F1CC1E;
}
.grey {
    background-color: rgba(17,17,19,0.12);
      color: #111113;
  font-family: 'Poppins';
  font-weight: 400;
  font-size: 11px;
  letter-spacing: 0.98px;
  line-height: 24px;
  align-self: left;
  width: 100%;
  text-align: left;
}
p {
    font-weight: 600;
      opacity: 0.56;
  color: #111113;
  font-family: 'Poppins';
  font-size: 17px;
  font-weight: 600;
  letter-spacing: 0.4px;
  line-height: 27px;
  align-self: left;
  text-align: left;
}

i {
    align-self: right;
  text-align: right;
}

img{
    max-width: 100%;
}

.signature{
    text-align: left;
}

.signature p{
    text-align: left;
    font-family: "PT Serif";
  font-size: 10px;
  letter-spacing: 0.2px;
  line-height: 16px;
  opacity: 0.4;
  margin: 0;

}

@media (min-width: 1120px){

    .f{
        float: left;
    }

    .container {
    width: 80%;
    }
}
</style>
