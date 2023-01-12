<template>
  <div class="home">
    <h1>ASANDILE LANGENI</h1>
    <p>HELLO WORLD</p>
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
<style scoped>
.home{
  background-image: url(https://i.postimg.cc/KcTzh7JW/pexels-riccardo-bertolo-4245826.jpg);
  background-size: cover;
  background-repeat: no-repeat;
  height: 100vh;
}
</style>
