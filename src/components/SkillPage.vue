<template>
    <body>
        <h1 class="about">About Me</h1>
        <div class="card mb-3 skill" style="max-width: 540px;">
  <div class="row g-0">
    <div class="col-md-4">
      <img src="./../assets/about.jpg" class="img-fluid rounded-start pic" alt="...">
    </div>
    <div class="col-md-8">
      <div class="card-body">
        <h5 class="card-title">Card title</h5>
        <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
        <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
      </div>
    </div>
  </div>
</div>
<img src="./../assets/png3.png" class="aboutPNG">
</body>
</template>
<script>
export default {
    name:"SkillPage"
}
</script>
<style scoped>
body{
    background-color: #212529;
    height: 100vh;
}

.skill{
    gap: 20px;
    padding: 100px 60px;
    margin: 0 100px;
    top: 20px;
    color: azure;
    text-align: justify;
    background-color: #FDD700;
    backdrop-filter: blur(0px) saturate(200%);
    -webkit-backdrop-filter: blur(0px) saturate(200%);
    background-color: rgba(0, 0, 0, 0.6);
    border-radius: 12px;
    border: 1px solid rgba(209, 213, 219, 0.3);
}

.about{
    padding-top: 60px;
    color: #FDD700;
    font-family: 'Caprasimo', cursive;
}
.pic{
    /* transform: rotate(-90deg); */
    border: 2px solid #FDD700;
}
.aboutPNG{
    position: absolute;
    right: 100px;
    top: 120vh;
}

</style>