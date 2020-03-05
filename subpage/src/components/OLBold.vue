<template>
    <div class="container">
        
        <label for="lista">Lista</label>
        <ol name="lista">
            <div >
            <li class="row "><p class="col-1"><strong>1</strong></p><p class="col-10">Poppins 20pt Regular. Line height 32. Letter spacing 0,4.<strong> Why Many B2B </strong>Service Marketplaces Failed because.</p> </li>
            <hr>
            <li class="row "><p class="col-1"><strong>2</strong></p><p class="col-10"><strong>All those functions</strong> work together within a coherent system design of Diagram.</p></li>
            <hr>
            <li class="row "><p class="col-1"><strong>3</strong></p><p class="col-10"><strong>Poppins 20pt Bold.</strong></p></li>
            <hr>
            <li class="row " id='ULLS08'><p class="col-1"><strong>4</strong></p><p class="col-10">Poppins 20pt Bold.  Line height 32. Letter-spacing 0,8. Why Many B2B Service Marketplaces Failed because.</p></li>
            <hr>
            </div>
        </ol>
    </div>
</template>

<script>
export default {
  name: 'ULSquares',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css?family=Poppins:400,700&display=swap');


.container {
    width: 100%;
}

ul{
    list-style-type:georgian;
    
}

label {
    display: none;
}

ol {
    font-family: 'Poppins' ;
    font-weight: 600;
}
li {
    font-family: 'Poppins' ;
    font-weight: 600;
    font-size: 17px;
    letter-spacing: 0.24px;
    line-height: 27px;
    text-align: left;
    color: #111113;
}

strong {
        letter-spacing: 0.8px;
        line-height: 32px;
    }


@media (min-width: 1120px){
    li {
        font-family: 'Poppins' ;
        font-weight: 600;
        font-size: 20px;
        letter-spacing: 0.4px;
        line-height: 32px;
        text-align: left;
        color: #111113;
    }

    strong{
        letter-spacing: 0.8px;
    }

    .container {
    width: 70%;
}
}
</style>
