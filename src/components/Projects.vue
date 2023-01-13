<template>
    <div>
        <h1>PROJECTS</h1>
        <div class="card" style="width: 18rem;">
  ``<img src="" class="card-img-top" alt="">
  <div class="card-body">
    <h5 class="card-title">Card title</h5>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    <a href="#" class="btn btn-primary">Go somewhere</a>
  </div>
</div>
    </div>
</template>
<script>
export default {
    name: 'Projects',
data() {
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