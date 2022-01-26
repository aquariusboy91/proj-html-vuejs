<template>
     <div class="container mt-container h-500">
          <div class="row h-350 justify-content-center">
            <div class="col-8 text-center d-flex flex-column align-items-center">
                 <h3>Trusted Partners</h3>
                 <hr>
                 <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque pariatur voluptatibus exercitationem expedita aspernatur corporis, culpa deserunt nobis at unde ea cum quas laudantium illum sit maiores neque quis assumenda.</p>
            </div>
        </div>
        <div class="row row-cols-5 justify-content-center w-60">
            <div class="d-flex justify-content-center">
                <img src="../assets/img/estate1.png" alt="">
            </div>
            <div class="d-flex justify-content-center">
                <img src="../assets/img/estate2.png" alt="">
            </div>
            <div class="d-flex justify-content-center">
                <img src="../assets/img/estate3.png" alt="">
            </div>
            <div class="d-flex justify-content-center">
                <img src="../assets/img/estate4.png" alt="">
            </div>
            <div class="d-flex justify-content-center">
                <img src="../assets/img/estate5.png" alt="">
            </div>
        </div>
     </div>
  
</template>

<script>
export default {
    name : 'Partners',

}
</script>

<style lang="scss" scoped>
    *{
        font-family: 'Libre Franklin', sans-serif;
    }
    .mt-container {
        margin-top: 7em;  
    }  
     p {
        color: grey;
        font-size: 12px;
        line-height: 2em;
    }
    .h-500 {
        height: 400px;
    }
    img {
        width: 170px;
        height: 100px;
    }
    .w-60 {
        width: 85%;
        margin:auto;
    }
    hr {
            color: orange;
        }

</style>