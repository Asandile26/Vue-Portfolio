<template>
    <div>
  <nav class="navbar shadow-sm">
          <div class="container">
            <a class="navbar-brand text-black fw-bold fs-4" href="#">
              <img class="logo" src="https://i.postimg.cc/7L9z7BNt/a.gif" alt="">
            </a>
            <div class="dropdown">
              <button class="btn btn-secondary btn-light px-3" type="button" data-bs-toggle="dropdown" aria-expanded="false">
                  <span class="navbar-toggler-icon"></span>
              <i class="fas fa-bars"></i>
              </button>
              <ul class="dropdown-menu ">
                <li><router-link to="/">Home</router-link></li>
                <li><router-link to="/about">About</router-link></li>
                <li><router-link to="/resume">Resume</router-link></li>
                <li><router-link to="/skills">Skills</router-link></li>
                <li><router-link to="/projects">Projects</router-link></li>
                <li><router-link to="/Testimonials">Testimonials</router-link></li>
                <li><router-link to="/contact">Contact</router-link></li>
              </ul>
            </div>
          </div>
        </nav>
    </div>
</template>
<script>
export default {
    name: 'NavBar'
}
</script>
<style scooped>
.logo {
    height: 10vh;
}
</style>