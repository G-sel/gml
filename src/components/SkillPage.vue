<template>
    <body>
        <h1 class="about">Get to know me</h1>
        <div class="card mb-3 skill" style="max-width: 540px;">
  <div class="row g-0">
    <div class="col-md-4">
      <img src="./../assets/about.jpg" class="img-fluid rounded-start pic" alt="...">
    </div>
    <div class="col-md-8">
      <div class="card-body">
        <h5 class="card-title desc">Bachelor's degree in Computer Science</h5>
        <p class="card-text desc">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
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
    background-color: #201920;
    height: 100vh;
}

.skill{
    gap: 20px;
    padding: 20px 60px;
    margin: 0 100px;
    top: 20px;
    height: 250px;
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
    padding-top: 70px;
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

/* responsive design */
@media screen and (max-width: 1230px) 
{   
    .pic{
    height: 400px;
    top: 100px;
}
}

@media screen and (max-width: 1290px) and (min-width: 1100px)
{ 
    .about{
        font-size: 30px;
    } 
 
    .pic{
    height: 200px;
    top: 100px;
    }
    .aboutPNG{
      right: 100px;
      top: 120vh;
      height: 300px;
    }

}

@media screen and (max-width: 1100px) and (min-width: 500px)
{ 
  body{
    height: 130vh;
  }
    .about{
        font-size: 20px;
    }  
    .desc{
      font-size: 15px ;
      
    }  
    .skill{
      height: 400px;
    }  
    .pic{
    height: 150px;
    }
    .aboutPNG{
      right: 130px;
      top: 175vh;
      height: 300px;
    }

}


</style>