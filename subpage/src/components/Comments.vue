<template>
    <div class="container">
        <!-- data-href url do zmiany , localhost podany jako test-->
        <div class="fb-comments" data-href="http://localhost/" data-width="100%" data-numposts="5"></div>
    </div>
</template>

<script>

export default {
  name: 'Comments',
}
</script>


<style scoped>
@import url('https://fonts.googleapis.com/css?family=Poppins:400,700&display=swap');


.container {
    width: 100%;
    padding: 0;
}



@media (min-width: 1120px){

    
    .container {
    width: 70%;
}
}
</style>
