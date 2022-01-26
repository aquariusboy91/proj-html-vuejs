<template>
    <div class="container-fluid h-500 mt-container">
        <div class="row h-350 justify-content-center">
            <div class="col-8 text-center d-flex flex-column align-items-center">
                 <h3>Specialist In Modern Construction</h3>
                 <hr>
                 <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque pariatur voluptatibus exercitationem expedita aspernatur corporis, culpa deserunt nobis at unde ea cum quas laudantium illum sit maiores neque quis assumenda.</p>
            </div>
        </div>
        <div class="row d-flex justify-content-center">
            <img v-for="(works,index) in portimg"
                :key="index"
                :src="require(`../assets/img/${works.img}`)"
                 alt="">
         </div>
         <div class="d-flex justify-content-center mt-5">
            <hr>
            <a href=""><span class="link-project">view all projects</span></a>
            <hr>
         </div>
    </div>
  
</template>

<script>
export default {
    name: 'MainPortfolio',
    data() {
     return {
         portimg: [
             
             {img: 'house1.jpg'},
             {img: "house2.jpg"},
             {img: "house3.jpg"},
         ]

         
     }
    }
}
</script>

<style  lang="scss" scoped>
     *{
        font-family: 'Libre Franklin', sans-serif;
    }
    .mt-container {
        margin-top: 7em;

        }   
    img {
        width: 25%;
        height: 250px;
        padding-right: 1em;
    }
    hr {
        display: inline-block;
        color: orange;
    }
    .link-project {
        margin-right: 2em;
        margin-left: 2em;
        font-size: 10px;
        text-transform: uppercase;
    }
    a {
        text-decoration: none;
        color: gray;
    }

    .h-500 {
        height: 600px;
    }
     p {
        color: grey;
        font-size: 12px;
        line-height: 2em;
    }


</style>