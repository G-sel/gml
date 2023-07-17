<template>
    <body>
        <h3 class="about">Get to <a class="know-outline">know</a> me</h3>
<!-- 1st card -->
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
<!-- 2nd card -->
<div class="card mb-3 skill right" style="max-width: 540px;">
  <div class="row g-0">
    
    <div class="col-md-8">
      <div class="card-body">
        <h5 class="card-title desc">Bachelor's degree in Computer Science</h5>
        <p class="card-text desc">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
        <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
      </div>
    </div>
    <div class="col-md-4">
      <img src="./../assets/about.jpg" class="img-fluid rounded-start pic2" alt="...">
    </div>
  </div>
</div>

<!-- svg assets -->
<svg class="svg1" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
  <path fill="#E8DAFF" d="M44.2,-66.4C54.2,-62.3,57.2,-44.9,60.8,-29.9C64.4,-14.8,68.6,-2.2,69.9,12.2C71.1,26.5,69.4,42.6,61.2,54C52.9,65.4,38,72.2,22.2,77.9C6.3,83.6,-10.5,88.4,-21.3,81.2C-32.1,74.1,-36.9,55.1,-43.5,41.2C-50.2,27.3,-58.6,18.5,-66.3,5.8C-73.9,-6.9,-80.6,-23.4,-74.5,-32.9C-68.4,-42.4,-49.4,-44.9,-34.9,-46.9C-20.3,-49,-10.2,-50.5,3.5,-55.9C17.1,-61.3,34.2,-70.5,44.2,-66.4Z" transform="translate(100 100)" />
</svg>
<img src="./../assets/png3.png" class="aboutPNG">
</body>
</template>
<script>
export default {
    name:"SkillPage"
}
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Pacifico&display=swap');
body{
    background-color: #212529;
    height: 100vh;
}

.right{
    /* padding: 20px 60px;
    margin: 0 100px; */
    /* top: 10px; */
    height: 250px;
    left: 45%;
    color: azure;
    text-align: justify;
    background-color: #FDD700;
    backdrop-filter: blur(0px) saturate(200%);
    -webkit-backdrop-filter: blur(0px) saturate(200%);
    background-color: rgba(0, 0, 0, 0.6);
    border-radius: 12px;
    border: 1px solid rgba(209, 213, 219, 0.3);
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
    padding-top: 30px;
    color: #FDD700;
    font-family: 'Caprasimo', cursive;
}
.know-outline{
  /* -webkit-text-stroke: 2px rgb(209, 135, 195); */
  font-family: 'Pacifico', cursive;
  color: #FDD700;
  text-decoration: none;
}
.svg1{
    height: 300px;
    position: absolute;
    right: 18vw;
    top: 105vh;
}
.aboutPNG{
    position: absolute;
    right: 15vw;
    top: 110vh;
    height: 300px;
}
.pic{
    /* transform: rotate(-90deg); */
    border: 2px solid #FDD700;
    transform: scaleX(-1);
}
.pic2{
    /* transform: rotate(-90deg); */
    border: 2px solid #FDD700;
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