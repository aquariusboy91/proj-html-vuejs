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
                <span class="title-section">latest tweets</span>
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
                 <div class="share d-flex justify-content-between align-items-center mt-1">
                         <i class="far fa-heart margin-left"></i>
                         <i class="fas fa-share-square p-r"></i>
                         <span class="mt-0">22h</span>
                     </div>
            </div>
            <div class="col-3">
                <span class="title-section">contact us today</span>
                <ul>
                    <li>
                        <i class="fas fa-globe p-r1"></i>
                        <span>Corporate Location</span><br>
                        <span class="p-r2">1600 Amphitheatre Parkway</span><br>
                        <span class="p-r2">London WC1 1BA</span>
                    </li>
                    <li>
                        <i class="fas fa-home p-r1"></i>
                        <span>Residential Location</span><br>
                        <span class="p-r2">9521 Broadsberry Avenue</span><br>
                        <span class="p-r2">Paddington RC7 9ZA</span>
                    </li>
                    <li>
                        <i class="fas fa-phone p-r1"></i>
                        <span>1.800.458.556 / 1.800.532.2112</span><br>
                        
                    </li>
                    <li>
                        <i class="fas fa-envelope p-r1"></i>
                        <span>info@your-domain.com</span><br>
                        
                    </li>
                    <li>
                        <i class="fas fa-clock p-r1"></i>
                        <span>Monday - Friday: 9:00AM - 6:00PM</span><br>
                        
                    </li>
                    <li>
                        <i class="fas fa-clock p-r1"></i>
                        <span>Saturday - Sunday: 9:00AM - 12:00PM</span><br>
                       
                    </li>
                </ul>
            </div>
            <div class="col-2">
                <span class="title-section">find us</span>
                <div class="findus"></div>
            </div>
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
        background-color: rgb(32, 32, 32);
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
        background: rgb(37, 37, 37);
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
        background-color: rgb(20, 20, 20);
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

    .margin-left {
        margin-left: 3em;
    }
    .share {
        font-size: 10px;

    }
    .p-r{
        padding-right: 15em;
    }
    
    ul {
        list-style-type: none;
        margin-top: 0.5em;
    }
    .p-r1 {
        padding-right: 1em;
    }

    .p-r2 {
        padding-left: 2em;
    }
    li {
        line-height: 2em;
        color: gray;
    }
    .title-section {
        font-size: 16px;
        font-size: bold;
        text-transform: uppercase;
        color: orange;
    }
    .findus {
        width: 250px;
        height: 300px;
        background-image: url(../assets/img/findus1.png);
        margin-top: 1em;
    }
    
    

</style>