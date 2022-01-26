<template>
    <div class="container-fluid d-flex justify-content-center align-items-center">
        <div class="row justify-content-center">
            <div class="col-3 d-flex flex-column">
                <img src="..\assets\img\footer-logo.png" alt="" class="logo">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Et laborum voluptate, aut, vel aliquid molestiae quisquam eveniet enim temporibus dicta quos.</p>
                <div class="d-flex align-items-start flex-column">
                    <a href=""><div class="btn-explore">get a free quote</div></a>
                </div>

            </div>
            <div class="col-3 card-tweet">
                <span>Latest Tweets</span>
                <div>
                    <div class="rounded mt-2">
                        <img src="..\assets\img\cropcircle.png">
                    </div>
                    <span class="tweet">ThemeFusion</span><br>
                        <span class="tweet2">@Theme_Fusion</span>
                        <p class="p">Do you need sublime WordPress hosting for your next website? Take advantage of exclusive partner offers that we have secured just for you, & launch your site in seconds with<a href="">#avada</a>
                        on WP engine hosting & get 30% <br> Off This Black Friday<a href="">bit.ly/3kjLLE2 #BlackFriday2020</a></p>
                </div>
            </div>
            <div class="col-2"></div>
            <div class="col-2"></div>
        </div>
    </div>
  
</template>

<script>
export default {
    name: 'Footer',

}
</script>

<style lang="scss" scoped>
    .container-fluid {
        height: 400px;
        background-color: black;
    }
    .logo {
        width: 170px;
        height: 50px;
    }
    .btn-explore {
        display: inline-block;
        background-color: #EFC338 ;
        text-transform: uppercase;
        font-size: 15px;
        color: rgb(90, 90, 90);
        padding: 0.5em 1.2em 0.5em 1.2em;
        border-radius: 4px;
        margin-bottom: 1em;
    }
    p {
        font-size: 12px;
        color: gray;
        line-height: 2em;
        margin-top: 1em;
        display: inline-block;
    }
    .rounded {
        height: 24px;
        width: 24px;
        border-radius: 50%;
        display: inline-block;
    }
    img {
        width: 24px;
        height: 24px;
    }
    .tweet {
        font-size: 12px;
        vertical-align: 0.3em;
        padding-left: 0.5em;
        color: white;
    }
    .tweet2 {
         font-size: 12px;
         position: absolute;
         top:46px;
         padding-left: 3em;
         font-size: 11px;
         color: gray;
    }
    .card-tweet {
        position: relative;
    }
    .p {
        padding-left: 2.5em;
        line-height: 1.2em;
        color: white;
        display: inline-block;
        margin-bottom: 0;
    }
    .margin {
        margin-top: 0;
    }
    

</style>