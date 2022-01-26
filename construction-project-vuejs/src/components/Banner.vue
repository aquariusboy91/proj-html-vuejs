<template>
    <div class="container-fluid justify-content-center align-items-center d-flex">
        <div class="row justify-content-center">
            <div class="col-6">
                 <h3>Building Inspiring Spaces</h3>
                 <hr>
                 <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque pariatur voluptatibus exercitationem expedita aspernatur corporis, culpa deserunt nobis.</p>
            </div>
            <div class="col-4 d-flex justify-content-center align-items-center flex-column">
                <a href=""><div class="btn-explore">get a free quote</div></a>
                <p>Only takes a few seconds!</p>
            </div>
        </div>
    </div>
  
</template>

<script>
export default {
    name: 'Banner'

}
</script>

<style lang="scss" scoped>
    .container-fluid {
        background-image: url(../assets/img/calltoaction.jpg);
        height: 300px;
        background-size: cover;
        background-repeat: no-repeat;
        background-position: bottom;
    }
    h3 {
        color:white;
    }
    p {
        color:white;
        font-size: 14px;
    }
    hr {
        color: orange;
    }
    .btn-explore {
        display: inline-block;
        background-color: #EFC338 ;
        text-transform: uppercase;
        font-size: 15px;
        color: gray;
        padding: 0.5em 1.2em 0.5em 1.2em;
        border-radius: 4px;
        margin-bottom: 1em;
    }
    
</style>