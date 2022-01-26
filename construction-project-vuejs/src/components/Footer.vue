<template>
    <div class="container-fluid d-flex justify-content-center align-items-center">
        <div class="row justify-content-center">
            <div class="col-3 d-flex flex-column">
                <img src="..\assets\img\footer-logo.png" alt="" class="logo">
                <p>We are specialists in the construction of unique and exclusive properties. Our work inspires. We pride ourselves on delivering outstanding quality and design for leading clients across the world.</p>
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
                        <p class="p">Do you need sublime WordPress hosting for your next website? Take advantage of exclusive partner offers that we have secured just for you, & launch your site in seconds with <a href=""> #avada</a>
                        on WP engine hosting & get 30% <br> Off This Black Friday <a href=""> bit.ly/3kjLLE2 #BlackFriday2020</a></p>
                </div>
                <div class="offer d-flex justify-content-center align-items-center flex-column">
                    <img class="logowp" src="..\assets\img\logowpp.png">
                    <p class="p-wp">Launch your site in seconds with Avada Website Builder on WP Engine</p>
                    <a href=""><div class="btn-wp">VISITE WEBSITE</div></a>
                    <span class="offer-wp">30% Off</span>
                    <p class="p-wp margin-top">5 months free on annual shared plan</p>
                     <a href=""><div class="btn-wp-avada">avada30</div></a>

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
        height: 450px;
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
    a {
        text-decoration: none;
    }
    .offer {
        width: 93%;
        height: 200px;
        background: rgb(43, 43, 43);
        margin-left: 1.8em;
        margin-top: 1em;
        border-radius: 3px;
    }

    .logowp {
        width: 100px;
        height: 20px;
    }
    .p-wp {
        width: 60%;
        font-size: 8px;
        text-align: center;
        color: white;
        margin-bottom: 0.5em;
    }
    .btn-wp {
        background-color: rgb(34, 34, 34);
        font-size: 4px;
        padding: 1em 2em 1em 2em;
        border-radius: 4px;
        color: white;

    }

    .offer-wp {
        font-size: 15px;
        color: rgb(0, 179, 0);
        font-weight: bold;
        margin-top: 0.5em;
    }

    .btn-wp-avada {
        background-color: rgb(1, 187, 1);
        font-size: 10px;
        padding: 0.5em 4em 0.5em 4em;
        border-radius: 4px;
        color: white;
        font-weight: bold;

    }
    .margin-top {
        margin-top: 0;
    }
    
    
    

</style>