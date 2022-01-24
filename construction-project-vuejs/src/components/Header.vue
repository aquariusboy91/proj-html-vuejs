<template>
    <div class="container">
        <div class="row">
            <nav class="navbar navbar-expand-lg navbar-light">
  <div class="container-fluid">
    <a class="navbar-brand" href="#"> <img src="..\assets\img\construction_logo.png" alt="" class="logo"></a>
    <div class="navbar-collapse justify-content-end" id="navbarNavDropdown">
      <ul class="navbar-nav">
        <li class="nav-item me-2">
          <a class="nav-link active" aria-current="page" href="#">HOME</a>
        </li>
        <li class="nav-item me-2">
          <a class="nav-link" href="#">ABOUT</a>
        </li>
        <li class="nav-item me-2">
          <a class="nav-link" href="#">SERVICES </a>
        </li>
        <li class="nav-item me-2">
          <a class="nav-link" href="#">WORK </a>
        </li>
        <li class="nav-item me-2">
          <a class="nav-link" href="#">ARTICLES</a>
        </li>
        <li class="nav-item quote ms-2 pe-1 ps-1">
          <a class="nav-link" href="#">GET QUOTE</a>
        </li>
        
      </ul>
    </div>
  </div>
</nav>
        </div>
    </div>
  
</template>

<script>
export default {
     name: 'Header',
};
</script>

<style lang="scss" scoped>
    #navbarNavDropdown {
        font-size: 11px;
    
    }
    * {
        font-family: 'Libre Franklin', sans-serif;
    }
    .logo {
        width: 100%;
        height: 60px;

    }
    .quote {
        background-color: #F4C939;
    }
    
    #navbarNavDropdown .navbar-nav > li > a:hover{
    color:#c7a021 ;
}

</style>