<template>
<div class="container">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <div class="row">
        <div class="col-xl-5 px-0 order-xl-2">
            <img src="../assets/pixel.jpg" alt="image">
        </div>

        <div class="black col-xl-7 order-xl-1">
            <br>
            <h3><span>Cześć, jestem Bazlac.</span><br>Piszę, mówię i tłumaczę, jak zostać projektantem interfejsów</h3>
            <br>
            <p>Jeśli podoba Ci się tutaj, to włącz powiadamianie o nowych rzeczach. Obiecuje wysyłać maksymalnie jedną wiadomość miesięcznie!</p>
            <br>
            <label for="exampleFormControlInput1" style="display: none;">Email address</label>
            <form action="POST">
            <input type="email" class="form-control" placeholder="Twój-email@adres.com">
            <button type="button" class="btn fa fa-envelope"></button>
            </form>
        </div>
        
    </div>
</div> 
</template>

<script>
export default {
  name: 'Newsletter',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.black{
    background-color: black;
}

button {
    display: inline;
    padding: 20px;
    font-size: 25px;
    width: 25px;
    text-align: center;
    text-decoration: none;
    margin: 5px 2px;
    border-radius: 50%;
    box-sizing: content-box;
    background: #F13A12;
      color: white;
}

img{
    max-width: 100%;
    height: 676px;
}

span{
    opacity: 0.56;
}

h3 {
    color: #FFFFFF;
  font-family: Poppins;
  font-size: 36px;
  font-weight: bold;
  letter-spacing: 0.4px;
  line-height: 50px;
  margin-top: 50px
}

p{
      opacity: 0.56;
  color: #FFFFFF;
  font-family: Poppins;
  font-size: 20px;
  letter-spacing: 0.4px;
  line-height: 32px;
}

input{
    background-color: #FFFFFF;
    width: 70%;
    display: inline;
    border-radius: 25px;
    height: 60px;
    margin-right: -60px;
      color: #111113;
  font-family: 'Poppins';
  font-size: 16px;
  font-weight: bold;
  letter-spacing: 0.6px;
  line-height: 36px;
}

.container {
    width: 100%;
}


@media (min-width: 1120px){
    .container {
    width: 80%;
    }
}
</style>
