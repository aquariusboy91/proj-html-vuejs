<template>
    <div class="container-fluid d-flex justify-content-center align-items-center">
        <div class="row h-350 w-600 justify-content-center align-items-center">
            <div class="col-8 text-center d-flex flex-column align-items-center">
                 <h3>Our Home Owners Say</h3>
                 <hr>
                 <div class="rounded"><img src="..\assets\img\mom-modified.png"></div>
                 <p>"A house is made with walls and beams; a home is built with love and dreams."</p>
                 <span>harry smith <i class="fas fa-circle"></i> new home owner</span>
            </div>
        </div>
    

    </div>
  
</template>

<script>
export default {
    name: 'MainFeedback',

}
</script>

<style lang="scss" scoped>
    .container-fluid {
    background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(../assets/img/nicehouse.jpg);
    height: 400px;
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    }
    .rounded {
        height: 80px;
        width: 80px;
        border-radius: 50%;
    }
    img {
        height: 100px;
        width: 100px;
    }
    p {
        margin-top: 3em;
        color: white;
        font-size: 12px;

    }
    h3 {
        color:white;
    }
    span {
        text-transform: uppercase;
        color: white;
        font-size: 14px;
    }
    hr {
        color: #ffb285;
        border: 2px solid #ffa26c;
    }
    i {
        font-size: 5px;
        vertical-align: 0.7em;
        margin-right: 0.2em;
        margin-left: 0.2em;
    }

    .w-400 {
        width: 400px;
    } 
    .w-600 {
        width: 600px;
}
    
</style>