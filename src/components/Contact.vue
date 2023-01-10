<template lang="">
    <div>
    
<form action="https://formspree.io/f/mgebedqd" method="post">
    <div class="mb-3 text-center">
    <input type="text" class="form-control" id="exampleInputName1" name="Name" aria-describedby="nameHelp" placeholder="Enter your name" required v-model="name">
    </div>
    <div class="mb-3 text-align-center">
    <input type="text" class="form-control" id="exampleInputEmail1" name="Surname" aria-describedby="emailHelp" placeholder="Enter your surname" required v-modal="surname">
    <div id="emailHelp" class="form-text"></div>
    </div>
    <div class="mb-3 text-align-center">
    <input type="email" class="form-control" id="exampleInputmessage1" name="Email" placeholder="Enter your email" required v-modal="Email">
    <div id="messagedHelp" class="form-text"></div>
    </div>
    <div class="form-floating mb-4">
    <textarea class="form-control" placeholder="Leave a comment here" id="floatingTextarea"></textarea>
    <label for="floatingTextarea">Comments</label>
    </div>
    <input type="submit" id="submit" placeholder="Submit" v-on:click.prevent="submit">
</form>
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
    }
}
</script>
<style lang="">
    
</style>