<template>
<div class="container">
  <slot></slot>
</div>
    
</template>

<script>
export default {
  name: 'TextSlot',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css?family=Poppins:400,700&display=swap');
@import url('https://fonts.googleapis.com/css?family=PT+Serif&display=swap');

.container {
    width: 100%;
}

h2 {
    font-family: 'Poppins' ;
    font-weight: bold;
    font-size: 20px;
    letter-spacing: 0.2px;
    line-height: 30px;
    text-align: left;
    color: #111113;
}

h3 {
    font-family: 'Poppins' ;
      font-size: 28px;
  font-weight: bold;
  line-height: 38.2px;
  text-align: center;
  color: #111113;
}

h4 {
    opacity: 0.56;
    color: #111113;
    font-family: 'Poppins';
      font-size: 28px;
  line-height: 38.2px;
  text-align: center;
    }


p {
    font-family: 'PT Serif' ;
    font-size: 17px;
    line-height: 27px;
    letter-spacing: 0.36px;
    text-align: left;
    color: #111113;
}

@media (min-width: 1120px){
    h2 {
        font-family: 'Poppins' ;
        font-weight: bold;
        font-size: 24px;
        letter-spacing: 0.2px;
        line-height: 36px;
        text-align: left;
        color: #111113;
    }

    h3 {
    font-family: 'Poppins' ;
    font-weight: bold;
    font-size: 36px;
    letter-spacing: 0.4px;
    line-height: 46px;
    text-align: center;
    color: #111113;
}

h4 {
    opacity: 0.56;
    color: #111113;
    font-family: 'Poppins';
    font-size: 36px;
    letter-spacing: 0.4px;
    line-height: 46px;
    text-align: center;
    }

    p {
        font-family: 'PT Serif' ;
        font-size: 18px;
        line-height: 32px;
        letter-spacing: 0.4px;
        text-align: left;
        color: #111113;
    }

    .container {
    width: 70%;
}
}
</style>
