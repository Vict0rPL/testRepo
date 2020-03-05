<template>
    <div class="container">
        <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="100" height="100" viewBox="0 0 172 172" style=" fill:#000000;"><g fill="none" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none" text-anchor="none" style="mix-blend-mode: normal"><path d="M0,172v-172h172v172z" fill="none"></path><g fill="#cccccc"><path d="M55.04,17.2c-26.5525,0 -48.16,21.6075 -48.16,48.16v75.68h68.8v-68.8h-37.84v-6.88c0,-13.27625 7.71313,-24.08 17.2,-24.08h3.44v-24.08zM144.48,17.2c-26.5525,0 -48.16,21.6075 -48.16,48.16v75.68h68.8v-68.8h-37.84v-6.88c0,-13.27625 7.71313,-24.08 17.2,-24.08h3.44v-24.08z"></path></g></g></svg>
        <blockquote>If you think good design is expensive, you should look at the cost of bad design.</blockquote>
        <h5>— RALF SPETH </h5>
        <p>CEO @ Jaguar Land Rover You</p>
    </div>
</template>

<script>
export default {
  name: 'IconQuote',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css?family=Poppins:400,700&display=swap');


.container {
    width: 100%;
}

blockquote {
    font-family: 'Poppins' ;
        font-weight: bold;
        font-size: 28px;
        letter-spacing: 0.4px;
        line-height: 40px;
        text-align: center;
        align-self: center;
        color: #111113;
}

h5{
  color: #111113;
  font-family: Poppins;
  font-size: 16px;
  font-weight: bold;
  letter-spacing: 0.25px;
  line-height: 20px;
  text-align: center;
  align-self: center;
}

p{
  opacity: 0.56;
  color: #111113;
  font-family: Poppins;
  font-size: 13px;
  letter-spacing: 0.2px;
  line-height: 20px;
  text-align: center;
  align-self: center;
}


@media (min-width: 1120px){
    blockquote {
        font-family: 'Poppins' ;
        font-weight: bold;
        font-size: 36px;
        letter-spacing: 0.4px;
        line-height: 54px;
        text-align: center;
        align-self: center;
        color: #111113;
    }

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
    width: 80%;
}
}
</style>
