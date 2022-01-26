<template>
    <div class="container-fluid position-relative">
            <a href=""><div class="folder">
                <i class="fas fa-folder"></i>
                <span>Demos&nbsp;</span>
            </div></a>
            <a href=""><div class="folder position-sale">
                <span id="dollarbaby">$</span><span id="offer">39</span>
                <span id="onsale">On Sale </span>
            </div></a>
           <div class ="row h-500 flex-column justify-content-center align-items-center ">
               <div class="col-10 flex-column text-center d-flex justify-content-center">
                   <h1>Building Inspiring Spaces</h1>
                   <p>We build inspiring residential e commercial spaces</p>
                </div>
                <div class="col-10 d-flex justify-content-center">
                    <a href=""><div class="btn-explore">explore recent work</div></a>
                    <a href=""><div class="btn-explore quote">get quote today</div></a>
                </div>
           </div>
    </div>
</template>

<script>
import '@fortawesome/fontawesome-free/css/all.css';
import { library } from '@fortawesome/fontawesome-svg-core'
import { fas } from '@fortawesome/free-solid-svg-icons'
library.add(fas)
export default {
    name: "Jumbo",

}
</script>

<style lang="scss" scoped>
@import '@fortawesome/fontawesome-free';
    h1, p, span {
        font-family: 'Libre Franklin', sans-serif;
    }
    .container-fluid {
        background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(../assets/img/work.jpg);
        height: 600px;
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
    }
    .folder {
        background-color: white;
        display: inline;
        position: absolute;
        right: 0;
        margin-right: 0.5em;
        margin-top: 1em;
        border-radius: 5px;
        padding: 0.3em 0.7em 0.3em 0.7em;
        i {
            display: block;
            font-size: 20px;
            text-align: center;
            color: #3C4043;
        }   
        span {
            font-size: 10px;
            color: #3C4043;
        }
    }
    .position-sale {
        top: 12%;
        margin-top: 0.5em;
    }
    #dollarbaby {
        font-size: 10px;
        vertical-align: 0.8em;
        text-align: right;
        color: rgb(167, 196, 3);
        font-weight: bold;
    }
    #offer {
        font-size: 20px;
        text-align: right;
        color: rgb(167, 196, 3);
        font-weight: bold;
    }
    #onsale {
        display: block;
        text-align: center;
    }
    .h-500 {
        height: 600px;
    }
    h1 {
        text-transform: uppercase;
        color: white;
        font-size: 50px;
    }
    p {
        color: #EFC338;
        font-size: 22px;
    }
    .btn-explore {
        display: inline-block;
        background-color: rgb(36, 36, 36);
        text-transform: uppercase;
        font-size: 15px;
        color:white;
        padding: 0.5em 1.2em 0.5em 1.2em;
        border-radius: 4px;
    }
    .quote {
        margin-left: 1em;
        background-color: #EFC338 ;
        color: white;
    }

</style>