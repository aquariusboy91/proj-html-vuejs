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
            <div>
                <h1>ciao</h1>
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
    .container-fluid {
        background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(../assets/img/work.jpg);
        height: 500px;
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
        top: 12%
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

</style>