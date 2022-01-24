<template>
    <div class="container-fluid">
        <div clas="row">
            <i class="fas fa-folder text-white"></i>
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
        background-image: brightness(60%);
    }

</style>