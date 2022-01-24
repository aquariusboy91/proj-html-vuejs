<template>
  <div class="container-fluid bg-underjambo d-flex justify-content-center align-items-center">
      <div class="row position-relative">
          <h4>Do You have A Construction Project We Can Help With?</h4>
          <a href=""><div class="btn4 position-absolute">get quote today</div></a>
      </div>
  </div>
</template>

<script>
export default {
    name: 'UnderJambo',

}
</script>

<style lang="scss">
    *{
        font-family: 'Libre Franklin', sans-serif;
    }
    .bg-underjambo {
        background-color: #FED03D;
        text-align: center;
    }
    .container-fluid {
        height: 100px;
    }
    .btn4 {
        top: 145%;
        margin-left: auto;
        margin-right: auto;
        left: 0;
        right: 0;
        text-align: center; 
        background-color:  rgb(36, 36, 36);
        width: 180px;
        padding: 0.3em 0.8em 0.3em 0.8em;
        color: white;
        text-transform: uppercase;
        font-size: 13px;
        border: solid 2px white;
        
    }

</style>