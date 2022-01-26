<template>
    <div class="container-fluid h-500 mt-5 pt-5">
        <div class="row justify-content-center">
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
                <span>Great Services</span>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem aliquam quis quod nulla dicta, suscipit dolore tempora labore necessitatibus optio.</p>
            </div>
                <div class="counter d-flex flex-column justify-content-center align-items-center">
                    <div class="round-div mb-1 engine">
                        <i class="fas fa-cog"></i>
                    </div>
                    <span>Highest Stardards </span>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem aliquam quis quod nulla dicta, suscipit dolore tempora labore necessitatibus optio.</p>
            </div>
            <div class="counter d-flex flex-column justify-content-center align-items-center">
                <div class="round-div mb-1 users">
                    <i class="fas fa-users"></i>
                </div>
                <span>Professional Team</span>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem aliquam quis quod nulla dicta, suscipit dolore tempora labore necessitatibus optio.</p>
            </div>
            <div class="counter d-flex flex-column justify-content-center align-items-center">
                <div class="round-div mb-1 idea">
                    <i class="far fa-lightbulb"></i>
                </div>
                <span>Creative Solutions</span>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem aliquam quis quod nulla dicta, suscipit dolore tempora labore necessitatibus optio.</p>
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
        height: 500px;
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
    .engine {
        background-color: #6586b1;
        border-color:#6586b1 ;
    }

    .users {
        background-color: #fe6f1d;
        border-color: #fe6f1d;
    }

    .idea {
        background-color: #f9d03f;
        border-color: #f9d03f;
    }

    span {
        margin-top: 0.5em;
    }

    p {
        font-size: 12px;
        color: grey;
        text-align: center;
        line-height: 2em;
        margin-top: 0.5em
    }
    hr {
        color:orange;
    }

</style>