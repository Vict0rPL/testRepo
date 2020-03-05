<template>
    <div class="container">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
        <label for="lista">Lista</label>
        <ul name="lista">
            <div >
            <li class="row "><i class="fa fa-diamond col-1"></i><p class="col-10">Poppins 20pt Semibold. Line height 32. Letter spacing 0,4. Why Many B2B Service Marketplaces Failed because.</p> </li>
            <li class="row "><i class="fa fa-diamond col-1"></i><p class="col-10">All those functions work together within a coherent system design of Diagram.</p></li>
            <li class="row "><i class="fa fa-diamond col-1"></i><p class="col-10">Semibold</p></li>
            <li class="row " id='ULLS08'><i class="fa fa-diamond col-1"></i><p class="col-10">20pt;  Line height 32. Letter-spacing 0,8.</p></li>
            </div>
        </ul>
    </div>
</template>

<script>
export default {
  name: 'ULSquares',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css?family=Poppins:400,600&display=swap');


.container {
    width: 100%;
}

ul{
    list-style-type: none;
    
}
label {
    display: none;
}
p {
    font-family: 'Poppins' ;
    font-weight: 600;
    font-size: 17px;
    letter-spacing: 0.24px;
    line-height: 27px;
    text-align: left;
    color: #111113;
    display: inline;
}

#ULLS08{
        letter-spacing: 0.24px;
    }

.fa {
    /* transform: rotate(45deg); */
    /* margin: 10px; */
    padding-top: 8px;
  font-size: 15px;
  width: 15px;
  color: #111113;
}


@media (min-width: 1120px){
    p {
        font-family: 'Poppins' ;
        font-weight: 600;
        font-size: 20px;
        letter-spacing: 0.4px;
        line-height: 32px;
        text-align: left;
        color: #111113;
    }

    #ULLS08{
        letter-spacing: 0.8px;
    }

    .container {
    width: 70%;
}
}
</style>
