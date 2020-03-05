<template >
<div class="container" >
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <div class="row">
        <div class="col-xl-6">
            <a href="#" class="fa fa-facebook"></a>
            <a href="#" class="fa fa-twitter"></a>
            <a href="#" class="fa fa-linkedin"></a>
            <a href="#" class="fa fa-envelope"></a>
        </div>
        <div class="col-xl-6" id="example-2">
            <button v-on:click="example2.greet" class="btn btnText">kopiuj</button>
            <input readonly type="text" id="urlInput" class="input-group-text" value="https://balzac.blog/2x3faf">
            <button v-on:click="example2.greet" class="btn fa fa-paperclip"></button>
        </div>
    </div>
</div> 
</template>


<script>
import Vue from 'vue';
var example2 = new Vue({
  el: '#example-2',
  data: {
    name: 'Vue.js'
  },
  // define methods under the `methods` object
  methods: {
    greet: function (event) {
     
      if (event) {
        var copyText = document.getElementById("urlInput");
        copyText.select();
        copyText.setSelectionRange(0, 99999);
        document.execCommand("copy");
      }
    }
  }
})

export default {
  name: 'Share',
  data(){
    return {
      example2: example2
    }
  }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css?family=Poppins:400,700&display=swap');
button {
    display: inline;
    padding: 20px;
    font-size: 25px;
    width: 30px;
    text-align: center;
    text-decoration: none;
    margin: 5px 2px;
    border-radius: 50%;
    box-sizing: content-box;
    background: white;
      color:#111113;
      
}

.btnText {
  font-family: 'Poppins';
    font-weight: bold;
  letter-spacing: 0.6px;
  line-height: 36px;
  font-size: 16px;
}

input{
    width: 90%;
    display: inline;
    border-radius: 40px;
    background-color: rgba(17,17,19,0.12);
    box-shadow: 0 4px 24px 0 rgba(0,0,0,0.16);
    height: 60px;
    margin-right: -380px;
    margin-left: -360px;
    color: #111113;
    font-family: Poppins;
  font-size: 16px;
  letter-spacing: 0.6px;
  line-height: 36px;
  pointer-events:none;
}

.fa {
  padding: 20px;
  font-size: 25px;
  width: 25px;
  text-align: center;
  text-decoration: none;
  margin: 5px 2px;
  border-radius: 50%;
  box-sizing: content-box;
}

.fa:hover {
    opacity: 0.7;
}

.fa-facebook {
  background: #111113;
  color: white;
}

.fa-envelope {
  background: #111113;
  color: white;
}

.fa-twitter {
  background: #111113;
  color: white;
}

.fa-linkedin {
  background: #111113;
  color: white;
}


.container {
    width: 100%;
}



.fa:hover {
    opacity: 0.7;
}

@media (min-width: 1120px){
    .container {
    width: 80%;
    }
}
</style>
