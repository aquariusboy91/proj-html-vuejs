<template>
    <div class="container-fluid h-600 mt-container">
        <div class="row h-350 justify-content-center">
            <div class="col-8 text-center d-flex flex-column align-items-center">
                 <h2>Explore Recent Work</h2>
                 <hr>
                 <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque pariatur voluptatibus exercitationem expedita aspernatur corporis, culpa deserunt nobis at unde ea cum quas laudantium illum sit maiores neque quis assumenda.</p>
            </div>
        </div>
        <div class="row">
            <div class="col-12 d-flex justify-content-center text-center">
                <div class="services">
                    <div class="round-div mb-1">
                        <i class="far fa-building"></i>
                    </div>
                    <h4>Buildings</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
                </div>
                <div class="services">
                    <div class="round-div mb-1">
                        <i class="fas fa-sync"></i>
                    </div>
                     <h4>Renovate</h4>
                     <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
                </div>
                <div class="services">
                    <div class="round-div mb-1">
                       <i class="fas fa-home"></i>
                    </div>
                     <h4>Construct</h4>
                     <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
                </div>
                <div class="services">
                    <div class="round-div mb-1">
                        <i class="fas fa-truck"></i>
                    </div>
                     <h4>Exclusive</h4>
                     <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
                </div>
            </div>
        </div>
    </div>
  
</template>

<script>
export default {
    name: 'Main',
    

}
 
    
 
</script>

<style lang="scss">
    *{
        font-family: 'Libre Franklin', sans-serif;
    }
    .h-350 {
        height: 220px;
    }
    .h-600 {
        height: 500px;
    }

    .mt-container {
        margin-top: 7em;

    }

    hr {
        color: orange;
        width: 250px;
        border-top: 3px solid #d6b034;
    }

    .services {
        width: 300px;
        height: 200px;
        background-color: #e4f5ff;
        display: inline-block;
        margin-right: 1em;
        border-radius: 5px;
         p {
            font-size: 12px;
            color: gray;
            line-height: 2em;
        }
        h4 {
            color: rgb(78, 78, 78);
        }
    }
    .round-div {
        border: 2px solid gray;
        border-radius: 50%;
        text-align: center;
        margin: auto;
        height: 50px;
        width: 50px;
        display: inline-block;
        display: flex;
        justify-content: center;
        align-items: center;
        margin-top: 1em;
        color: gray;
       
    }
    p {
            font-size: 13px;
            color: gray;
            line-height: 2em;
        }

</style>