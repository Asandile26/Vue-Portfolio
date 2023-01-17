<template>
  <div class="home">
    <p>HELLO WORLD, I am</p>
    <h1>ASANDILE LANGENI</h1>
    <p>An Aspiring WEB DEVELOPER</p>
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
  justify-content: center;
  padding: 150px;
}
p{
  color:white
}
h1, p{
  box-shadow: 20px 30px 40px 11px rgb(28, 28, 86);
  justify-content: center;
  align-content: center;
  
   
}
@media screen and (max-width: 460px){
.home {
    flex-direction: column;
    /* display: flex; */
    font-size: medium;
  }
h1, p{
  box-shadow: none;
  font-weight: bold;
  text-shadow: 2.5px 2.5px 2.5px grey;
  justify-content: center;
  align-content: center;
  margin-right: 10rem;
}
}
.my-element {
  --animate-duration: 0.01s;
}
:root {
  --animate-delay: 5s;
}
p, h1{
animation: show;
animation-duration: 5s;
}

@keyframes show {
  0% {
    transform: scale(0);
  }
  100% {
    transition: scale(1.5);
  }
  
}

</style>
