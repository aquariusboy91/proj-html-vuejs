<template>
    <div class="container-fluid">
        <div class="row h-100 align-items-center">
            <div class="col-6 d-flex justify-content-start">
                <span> copyright 2012-2015 avada theme by theme fusion | all right reserved | powered by wordpress</span>
            </div>
            <div class="col-6 justify-content-end d-flex">
                <a href=""><i class="fab fa-twitter"></i></a>
                <a href=""><i class="fab fa-facebook-f"></i></a>
                <a href=""><i class="fab fa-youtube"></i></a>
                <a href=""><i class="fab fa-instagram p-r3"></i></a>
            </div>
            
        </div>
    </div>
  
</template>

<script>
export default {
    name: 'Subfooter',

}
</script>

<style lang="scss" scoped>
    .container-fluid {
        background-color: rgb(17, 17, 17);
        height: 60px;
    }
    span {
        text-transform: uppercase;
        font-size: 8px;
        color: rgb(78, 78, 78);
        padding-left: 3em;
    }
    .h-100 {
        height: 60px;
    } 
    a {
        color: rgb(78, 78, 78);
        padding-right: 1em;

        font-size: 12px;
    }
    .p-r3 {
        padding-right: 3em;
    }

</style>