<template>
    <div class="container">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
        <div>
            <i class="fa fa-square green"></i>
            <h5>Jak zaczac z UI</h5>
            <br>
            <br>
            <h1>Tytuł artykułu Poppins Bold 36 pt. Line height 46. Letter-spacing 0,4. Koniec. Kropka.</h1>
            <br>
            <p class="zjw">Zajawka artykułu PT Serif 22 pt. Line height 34, letter-spacing 0,24. Do niedawna na stronach WWW korzystało się tylko z Ariala, Timesa i Verdany i trzeba było się modlić.</p>
            <br>
            <p class="time">Czytanka na <strong>2 min.</strong></p>
            <p class="timestamp">23/05/2020</p>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Introduction',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css?family=Poppins:400,600,700&display=swap');
@import url('https://fonts.googleapis.com/css?family=PT+Serif&display=swap');

h1 {
    color: #111113;
  font-family: 'Poppins';
  font-size: 36px;
  font-weight: bold;
  letter-spacing: 0.4px;
  line-height: 46px;
  text-align: center;
  margin: auto;
}
h5 {
    font-size: 16px;
    font-weight: 600;
    letter-spacing: 0.2px;
    font-family: 'Poppins';
    display: inline;
    color: #111113;
    margin: auto;

}
i{
    display: inline;
}

.green{
    color:#25BF11;
    margin: 10px;
}
.time {
    color: #111113;
  font-family: 'Poppins';
  font-size: 13px;
  letter-spacing: 0.15px;
  line-height: 20px;
  text-align: center;
}
p {
    
  color: #111113;
  font-family: "PT Serif";
  font-size: 22px;
  letter-spacing: 0.24px;
  line-height: 34.5px;
  text-align: center;
}
.zjw {
    opacity: 0.56;
}
.timestamp{
    opacity: 0.32;
  color: #111113;
  font-family: 'Poppins';
  font-size: 13px;
  line-height: 20px;
  text-align: right;
}
</style>
