<template>
<div class="text-center container">
 <slot name="img"></slot>
</div> 
</template>

<script>
export default {
  name: 'StandaloneImage',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css?family=Poppins:400&display=swap');


.container {
    width: 100%;
    padding: 0;
}

img{
    max-width: 100%;
}

figcaption {
    font-family: 'Poppins' ;
    font-size: 11px;
    line-height: 17px;
    letter-spacing: 0.2px;
    text-align: left;
    color: #111113;
    opacity: 0.44;
}

@media (min-width: 1120px){
    img{
        max-width: 100%;
        
    }

    figcaption {
        font-family: 'Poppins' ;
        font-size: 13px;
        line-height: 20px;
        letter-spacing: 0.2px;
        text-align: left;
        color: #111113;
    opacity: 0.44;
    }

    .container {
    width: 80%;
    padding-left: 80px;
    padding-right: 80px;
    }
}
</style>
