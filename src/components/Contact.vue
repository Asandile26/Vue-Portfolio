<template lang="">
    <div class="Contact">
    <h1>CONTACT</h1>
<form action="https://formspree.io/f/mgebedqd" method="post">
    <div class="mb-3 text-center">
    <input type="text" class="form-control" id="exampleInputName1" name="Name" aria-describedby="nameHelp" placeholder="Enter your name" required v-model="name">
    </div>
    <div class="mb-3 text-align-center">
    <input type="text" class="form-control" id="exampleInputSurname1" name="Surname" aria-describedby="emailHelp" placeholder="Enter your surname" required v-modal="surname">
    <div id="emailHelp" class="form-text"></div>
    </div>
    <div class="mb-3 text-align-center">
    <input type="email" class="form-control" id="exampleInputEmail1" name="Email" placeholder="Enter your email" required v-modal="Email">
    <div id="messagedHelp" class="form-text"></div>
    </div>
    <div class="form-floating mb-4">
    <textarea class="form-control" placeholder="Leave a comment here" id="floatingTextarea"></textarea>
    <label for="floatingTextarea">Comments</label>
    </div>
    <input type="submit" id="submit" placeholder="Submit" v-on:click.prevent="handleSubmit">
</form>
<footer>
          <p><i class="bi bi-phone text-light"></i>0676555678</p>
          <p><i class="bi bi-envelope-fill"></i>asandilelangeni@gmail.com</p>
          <a href="https://mobile.twitter.com/la_nator21" target="_blank"> <i class="fa-brands fa-twitter"></i><i class="bi bi-twitter"></i></a>
          <a href="https://www.linkedin.com/in/asandile-langeni-05b027201/" target="_blank"><i class="fab fa-linkedin-in"></i><i class="bi bi-linkedin"></i></a>
          <a href="https://github.com/Asandile26"><i class="bi bi-github"></i></a>
      </footer>
    </div>
</template>
<script>
export default {
    name: 'Contact',
    data() {
        return {
            name: '',
            surname: '',
            email: '',
            message: '',
        }
    },
    methods: {
        handleSubmit(e) {
            e.preventDefault()
            alert(`Name: ${this.name}, Surname: ${this.surname}, Email: ${this.email}, Message: ${this.message}`)
        }
    }
}
</script>
<style>
form {
    justify-content: center;
    width: 35rem;
    margin: auto;
}
</style>