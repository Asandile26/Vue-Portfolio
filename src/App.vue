<template>
  <NavBar/>
  <router-view/>
  <Footer/>
</template>
<script>
import Footer from './components/Footer.vue';
import NavBar from './components/NavBar.vue';
export default{
  components: {
    Footer,
    NavBar
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: #2c3e50;
  height: 100vh;
}

nav {
  padding: 30px;
  
}

nav a {
  font-weight: bold;
  color: #2c3e50;
  text-decoration: none;
}

nav a.router-link-exact-active {
  color: #42b983;
  
}
footer{
  position: fixed;
  bottom: 0;
  color: white;
}
h1{
  color:white;
}
</style>
