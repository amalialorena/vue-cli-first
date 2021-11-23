<template>
  <div class="jumbotron">
      <img src="https://unsplash.it/600/300?image">
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    img {
        height: 80vh;
    }

</style>