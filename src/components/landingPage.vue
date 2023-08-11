<template>
    
    <body>
<div class="container">
    <svg class="svg1" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
  <path fill="#A7F0BA" d="M68.7,-20.5C78.2,7,67.6,42.8,47.3,55.3C26.9,67.8,-3.4,57,-23.6,40.5C-43.7,23.9,-53.9,1.5,-48.3,-20.6C-42.7,-42.7,-21.4,-64.6,4.1,-65.9C29.6,-67.3,59.2,-48,68.7,-20.5Z" transform="translate(100 100)" />
</svg>
    <p class="flex-start greet">Hello!</p>
    <h1 class="text-light flex-start name font">This is &nbsp;<p class="text-warning"> G-sel Loro</p></h1>
    <h1 class="text-light flex-start font">I'm a &nbsp;<p class="text-warning"> Web Developer</p></h1>
    <div class="button flex-start">
    <button class="button about bg-warning ">About Me</button>
    <!-- <button class="button download "><a href="./../assets/LORO_GSEL_RESUME.pdf" class="text-download text-warning" download>Download My CV</a></button> -->
    <div>
    <img src="./../assets/png2.png" class="pic">
    </div>
</div>
</div>
</body>
</template>

<script>
export default {
  name: 'landingPage'
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Kanit:ital,wght@0,300;0,400;1,300;1,400&display=swap');

body{
    height:90vh;
    background-color: #212529;
    font-family: 'Kanit', sans-serif;
}

.svg1{
    height: 500px;
    position: absolute;
    left: 0;
}

.text-download{
    text-decoration: none;
}


.pic{
    height: 450px;
    margin: 0;
    padding: 0;
    position: absolute;
    top: 140px;
    left: 0;
    transform: scaleX(-1);
}
.greet{
    font-family: 'Pacifico', cursive;
    color: #fdd700;
}
.container{
    padding-top: 60px;
}
.flex-start{
    display: flex;
    justify-content: center;
}
.name{
    padding-top: 10px;
    
}
.button{
    border-radius: 40px;
    padding: 10px 20px;
    gap: 5px ;
    margin: 0;
    font-size: 10px;
    font-family: 'Kanit', sans-serif;
}
.download{
    outline: 1px solid #fdd700;
    background-color: #212529 ;

    
}
.font{
    font-family: 'Caprasimo', cursive;
    z-index: 1;
}


.flex{
    display: flex;
    justify-content: center;
    align-content: center;
    margin: 0 150px;
}

/* responsive design */
@media screen and (max-width: 1230px) 
{ 
    .font{
        font-size: 30px;
    }    
    .pic{
    height: 400px;
    top: 100px;
}
.svg1{
    height: 400px;
    position: absolute;
    left: 0;
    top: 100px;
}
}

@media screen and (max-width: 1100px) and (min-width: 900px)
{ 
    .font{
        font-size: 30px;
    }    
    .pic{
    height: 300px;
    top: 100px;
}
.svg1{
    height: 300px;
    position: absolute;
    left: 0;
    top: 100px;
}
}

@media screen and (max-width: 900px) and (min-width: 700px)
{ 
    .font{
        font-size: 20px;
    }   
    .pic{
    height: 250px;
    top: 130px;
}
.svg1{
    height: 250px;
    position: absolute;
    left: 0;
    top: 130px;
}
}

@media screen and (max-width: 700px) and (min-width: 500px)
{ 
    .font{
        font-size: 20px;
    }   
    .button{
    border-radius: 40px;
    padding: 5px 5px;
    gap: 5px ;
}
    .pic{
    height: 250px;
    top: 250px;
}
.svg1{
    height: 250px;
    position: absolute;
    left: 0;
    top: 250px;
}
}


</style>