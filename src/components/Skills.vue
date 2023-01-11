<template>
  <div>
    <h1>SKILLS</h1>
    <div class="container bg-gradient" >
        <h2><i class="bi bi-filetype-html"></i>HTML</h2>
        <div class="progress" role="progressbar" aria-label="Animated striped example" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">
  <div class="progress-bar progress-bar-striped progress-bar-animated bg-secondary" style="width: 75%"><span>75%</span></div>
</div>
<h2><i class="bi bi-filetype-css"></i>CSS</h2>
        <div class="progress" role="progressbar" aria-label="Animated striped example" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">
  <div class="progress-bar progress-bar-striped progress-bar-animated bg-black" style="width: 65%"><span>65%</span></div>
</div>
<h2><i class="bi bi-bootstrap"></i>BOOTSTRAP 5</h2>
        <div class="progress" role="progressbar" aria-label="Animated striped example" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">
  <div class="progress-bar progress-bar-striped progress-bar-animated bg-info" style="width: 70%"><span>70%</span></div>
</div>
<h2><i class="bi bi-filetype-js"></i>JAVASCRIPT</h2>
        <div class="progress" role="progressbar" aria-label="Animated striped example" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">
  <div class="progress-bar progress-bar-striped progress-bar-animated bg-danger" style="width: 55%"><span>55%</span></div>
</div>
<h2>NODE</h2>
        <div class="progress" role="progressbar" aria-label="Animated striped example" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">
  <div class="progress-bar progress-bar-striped progress-bar-animated" style="width: 40%"><span>40%</span></div>
</div>
    </div>
  </div>
</template>
<script>
export default {
    name: 'Skills'
}
</script>
<style scoped>
h2{
  margin-right: 65rem;
}
.container{
  justify-content: center;
  align-items: center;
}
.container > div{
  width: 50%; 
}
h1{
  color:white;
}
</style>