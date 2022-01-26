<template>
  <div class="container-cards d-flex flex-column justify-content-center align-items-start">
      <div class="item animated wow fadeIn">
        <img :src="require(`../assets/img/${img}`)">
        <div class="overlay fade-overlay">
             <div class="round-div idea">
                    <a href=""><i class="fas fa-search"></i></a>
                </div>
    <div class="text">{{titolo}}<br>
        <span class="fs">Architecture, Buildings, Construction, News</span>
    </div>
  </div>
      </div>
      <h5>{{titolo}}</h5>
      <p class="date">{{date}}</p>
      <hr>
      <p>{{descr}}</p>
      
  </div>
</template>

<script>

export default {
    name: 'CardsNews',
    props: [
    'img',
    'titolo',
    'date',
    'descr',
    ]

}
</script>

<style lang="scss" scoped>
    .container-cards {
        width: 300px;
        margin-right: 2em;
        background-color: white;
    }
    img {
        width: 300px;
        height: 170px;
    }
    p {
        font-size: 10px;
        padding-left: 0.5em;
        padding-right: 0.5em;
        color: gray;
        line-height: 2em;
    }
    h5 {
        margin-top: 1em;
        padding-left: 0.5em;
        padding-right: 0.5em;
    }

    .date {
        font-size: 8px;
        padding-left: 1em;
        padding-right: 0.5em;
        color: gray;
    }
    hr {
        width: 80%;
        margin: auto;
        margin-bottom: 1em;
        color: orange;
    }
    .overlay {
    position: absolute;
    left: 0;
    right: 0;
    top: 0;
    bottom: 0;
    background-color: #FED03D;
    overflow: hidden;
    width: 100%;
    height: 100%;
    transition: .5s ease;
}
.item {
    position: relative;
    overflow: hidden;
    margin: 0px 0px;
}

.item:hover .overlay {
  bottom: 0;
  height: 100%;
  width: 100%;
}
.fade-overlay {
    height: 100%;
    opacity: 0;
}

.item:hover .fade-overlay {
  opacity: 1;
}
.text {
    color: white;
    font-size: 1.2vw;
    position: absolute;
    top: 50%;
    left: 50%;
    -webkit-transform: translate(-50%, -50%);
    -ms-transform: translate(-50%, -50%);
    transform: translate(-50%, -50%);
    text-align: center;
    font-size: 15px;
    margin-top: 1.3em;
}

.fs {
    font-size: 7px;
    font-weight: bold;
}
 .round-div {
        border: 2px solid white;
        border-radius: 50%;
        text-align: center;
        margin: auto;
        height: 40px;
        width: 40px;
        display: inline-block;
        display: flex;
        justify-content: center;
        align-items: center;
        margin-top: 1em;
        color: white;
        background-color: white;
       
    }
     a {
         color: #FED03D;
     }
     a:hover {
         color: #ffc400;
     }

</style>