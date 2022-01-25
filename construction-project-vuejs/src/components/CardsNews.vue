<template>
  <div class="container-cards d-flex flex-column justify-content-center align-items-start">
      <img :src="require(`../assets/img/${img}`)">
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
        color: rgb(167, 167, 167)
    }
    

</style>