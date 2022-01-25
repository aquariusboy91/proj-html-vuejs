<template>
  <div class="container-cards">
      <img :src="img">
      <h3>{{titolo}}</h3>
      <span>{{date}}</span>
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

</style>