<template>
  <div class="container-fluid">
    <h1>ABOUT</h1>
    <div class="intro col d-flex">
         <div class="photo-fluid">
            <img src="https://i.postimg.cc/bJPWBS18/t381-LPkw-400x400.jpg" alt="profile img" class="img-fluid">
                </div>
                <div>
            <p id="about-p1">Hello I am Asandile Langeni</p>
                        <p class="mt-4 " id="about-p">I am a 27 years aspiring web Developer, I am all about breaking boundaries in order to create something new. Coding excites me because the world is becoming more technological and coding provides me with the Skills to usher people to the right direction whether it is using apps or data mining. <br>
                        D.O.B   : 95-10-13 <br>
                        Location : Cape Town, Khayelitsha <br>
                        Email     : asandilelangeni@gmail.com <br>
                        Phone     : 067 6555 678 </p>
                      </div>
          </div>
  </div>
</template>
<style scoped>
.intro{
  display: flex;
  color:white;
  justify-content: center;
  align-items: center;
  /* flex-direction: column; */
}
/* .intro > div{
  width: 50%;
} */
@media screen and (max-width: 820px) {
.intro{
  flex-direction: column;
}
}
@media screen and (max-width: 400px) {
.photo{
width: 18rem;
justify-content: center;
}
}


</style>
