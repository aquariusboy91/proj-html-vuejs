<template>
    <div class="container-fluid h-500 mt-5 pt-5">
        <div class="row h-350 justify-content-center">
            <div class="col-8 text-center d-flex flex-column align-items-center">
                 <h3>Our Core Values</h3>
                 <hr>
                 <p class ="p">Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque pariatur voluptatibus exercitationem expedita aspernatur corporis, culpa deserunt nobis at unde ea cum quas laudantium illum sit maiores neque quis assumenda.</p>
            </div>
        </div>
        <div class="row d-flex justify-content-center">
            <div id="firstcounter" class="counter d-flex flex-column justify-content-center align-items-center">
                <div class="round-div mb-1">
                       <i class="fas fa-home"></i>
                </div>
                <span>2534</span>
                <p>planning application</p>
            </div>
                <div class="counter d-flex flex-column justify-content-center align-items-center">
                    <div class="round-div mb-1">
                        <i class="far fa-building"></i>
                    </div>
                    <span>896</span>
                    <p>completed projects</p>
            </div>
            <div class="counter d-flex flex-column justify-content-center align-items-center">
                <div class="round-div mb-1">
                    <i class="fas fa-users"></i>
                </div>
                <span>172</span>
                <p>trained professionals</p>
            </div>
            <div class="counter d-flex flex-column justify-content-center align-items-center">
                <div class="round-div mb-1">
                    <i class="fas fa-globe"></i>
                </div>
                <span>19</span>
                <p>international offices</p>
            </div>
    </div>
    </div>
  
</template>

<script>
export default {
    name: 'MainCoreValues',

}
</script>

<style lang="scss" scoped>
.h-500 {
        height: 600px;
        background-color: #f0ede6;
    }

    .p {
        color: grey;
        font-size: 12px;
        line-height: 2em;
    }
    .counter {
        width: 250px;
        i {
            font-size: 40px;
        }
    }
    #firstcounter {
        width: 250px;
    }
    .round-div {
        border: 2px solid #8faeb8;
        border-radius: 50%;
        text-align: center;
        margin: auto;
        height: 80px;
        width: 80px;
        display: inline-block;
        display: flex;
        justify-content: center;
        align-items: center;
        margin-top: 1em;
        color: white;
        background-color: #8faeb8;
       
    }

</style>