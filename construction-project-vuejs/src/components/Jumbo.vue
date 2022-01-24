<template>
    <div class="container-fluid position-relative">
            <div class="folder">
                <i class="fas fa-folder"></i>
                <span>Demos</span>
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
        padding: 0.3em 0.5em 0.3em 0.5em;
        i {
            display: block;
            font-size: 20px;
            text-align: center;
            color: #37393A;
        }   
        span {
            font-size: 10px;
            font-weight: bold;
            color: #37393A;
        }
    }

</style>