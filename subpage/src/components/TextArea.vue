<template>
    <div class="container">
        <h2>{{postTitle}}</h2>
        <br>
        <p>{{textContent}}</p>
        <slot></slot>
    </div>
</template>

<script>
export default {
  name: 'TextArea',
  props: ['postTitle', 'textContent']
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
    color: black;
}

p {
    font-family: 'PT Serif' ;
    font-size: 17px;
    line-height: 27px;
    letter-spacing: 0.36px;
    text-align: left;
    color: black;
}

@media (min-width: 1120px){
    h2 {
        font-family: 'Poppins' ;
        font-weight: bold;
        font-size: 24px;
        letter-spacing: 0.2px;
        line-height: 36px;
        text-align: left;
        color: black;
    }

    p {
        font-family: 'PT Serif' ;
        font-size: 18px;
        line-height: 32px;
        letter-spacing: 0.4px;
        text-align: left;
        color: black;
    }

    .container {
    width: 70%;
}
}
</style>
