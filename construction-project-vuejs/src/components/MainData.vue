<template>
    <div class="container-fluid d-flex justify-content-center align-items-center">
       <div class="counter d-flex flex-column justify-content-center align-items-center">
           <i class="fas fa-suitcase"></i>
           <span>2534</span>
           <p>planning application</p>
       </div>
        <div class="counter d-flex flex-column justify-content-center align-items-center">
           <i class="far fa-building"></i>
           <span>896</span>
           <p>completed projects</p>
       </div>
       <div class="counter d-flex flex-column justify-content-center align-items-center">
           <i class="fas fa-users"></i>
           <span>172</span>
           <p>trained professionals</p>
       </div>
       <div class="counter d-flex flex-column justify-content-center align-items-center">
           <i class="fas fa-globe"></i>
           <span>19</span>
           <p>international offices</p>
       </div>
    </div>
  
</template>

<script>
export default {
    name: 'MainData',

}
</script>

<style lang ="scss" scoped>
    .container-fluid {
        background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(../assets/img/lavoratorefede.jpg);
        width: 100%;
        height: 400px;
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center;
    }
    .counter {
        display: inline-block;
        padding-right: 4em;
        i {
            font-size: 50px;
            color:#F4C939;
        }
        span {
            font-size: 40px;
            color: #F4C939;
        }
        p {
            text-transform: uppercase;
            color: white;
            font-size: 12px;
        }
    }
   
    
    
    
    
    

</style>