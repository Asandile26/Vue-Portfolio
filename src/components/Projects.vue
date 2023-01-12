<template>
    <div>
        <h1>PROJECTS</h1>
        <div class="card" style="width: 18rem;" v-for="pro in Projects" :key="pro">
  <div class="card-body" >
    <img :src="pro.image" alt="">
    <h5 class="card-title">{{pro.title}}</h5>
    <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6>
    <a href="#" class="card-link">{{pro.githubLink}}</a>
    <a href="#" class="card-link">{{pro.netlifyLink }}</a>
  </div>
</div>
    </div>
</template>
<script>
export default {
    name: 'Projects',
    data(){
        return {
            Projects:[
                {
                id:0,
                image: '',
                title: 'Portfolio (HTML & CSS)',
                githubLink: 'https://github.com/Asandile26/portfolio2.git',
                netlifyLink: 'https://portfolioasandilelangeni.netlify.app'
                },
                {
                id:1,
                title: 'E-Commerce',
                image: '',
                githubLink: 'https://github.com/Asandile26/Ecommerce.git',
                netlifyLink: 'https://asandilelangeniecommerce.netlify.app'
                },
                {
                id:2,
                title: 'E-Commerce (Javascript)',
                image: '',
                githubLink: 'https://github.com/Asandile26/Project-E-commerce.git',
                netlifyLink: 'https://asandilelangeni-ecommerce.netlify.app'
                },
                {
                id:3,
                title: 'Spinner',
                image: '',
                githubLink: 'https://github.com/Asandile26/spinner2.0.git',
                netlifyLink: 'spinnertwo.netlify.app'
                },
                {
                id:4,
                title: 'Calculator',
                image: '',
                githubLink: 'https://github.com/Asandile26/calculator.git',
                netlifyLink: 'https://asandilelangenicalculator.netlify.app'
                },
                {
                id:5,
                title: 'Revision',
                image: '',
                githubLink: 'https://scouzerrevison.netlify.app',
                netlifyLink: 'https://github.com/Asandile26/Revision.git'
                }
            ]
        }
    }
}
</script>
<style>
    
</style>