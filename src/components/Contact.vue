<template lang="">
    <div class="Container-fluid">
    <h1>CONTACT</h1>
    <div class="container1-fluid">
        <form class="form container" action="https://formspree.io/f/mgebedqd" method="post">
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
                <div class="mb-4">
                <textarea class="form-control" placeholder="Leave a comment here" id="floatingTextarea"></textarea>
                <label for="floatingTextarea">Comments</label>
                </div>
                <input type="submit" id="submit" placeholder="Submit" v-on:click.prevent="handleSubmit">
 
           
        </form>
    </div>
    </div>
<footer>
          <p><i class="bi bi-phone text-light"></i>0676555678</p>
          <p><i class="bi bi-envelope-fill"></i>asandilelangeni@gmail.com</p>
          <a href="https://mobile.twitter.com/la_nator21" target="_blank"> <i class="fa-brands fa-twitter"></i><i class="bi bi-twitter"></i></a>
          <a href="https://www.linkedin.com/in/asandile-langeni-05b027201/" target="_blank"><i class="fab fa-linkedin-in"></i><i class="bi bi-linkedin"></i></a>
          <a href="https://github.com/Asandile26"><i class="bi bi-github"></i></a>
      </footer>
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
/* input{
    width: 100%;
} */
.container1{
    width: 35rem;
}
form {
    justify-content: center;
    /* width: 35rem; */
    margin:auto;
    width: 100%;
    
}
.form{
    border-style: outset;
    padding: 4rem;
    margin:0, 30rem;
    border-radius: 5px;
    width: 45rem;
}

@media screen and (max-width: 574px) {
    .form{
        width: 28rem;
    }
}
@media screen and (max-width: 461px) {
    .form{
        width: 24rem;
    }
}
</style>