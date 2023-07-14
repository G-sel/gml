<template>
    
    <body>
<div class="container">
    <p class="flex-start greet">HELLO!</p>
    <h1 class="text-light flex-start name font">This is &nbsp;<p class="text-warning"> G-sel Loro</p></h1>
    <h1 class="text-light flex-start font">I'm a &nbsp;<p class="text-warning"> Web Developer</p></h1>
    <div class="button flex-start">
    <button class="button about bg-warning ">About Me</button>
    <button class="button download text-warning">Download My CV</button>
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
.pic{
    margin: 0;
    padding: 0;
    position: absolute;
    top: 140px;
    right: 0;
    z-index: 0;
}
.pic2{
    margin: 0;
    padding: 0;
    position: absolute;
    top: 100px;
    left: 100px;
    height: 300px;
    width: 300px;
}
.greet{
    font-family: 'Kanit', sans-serif;
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
    padding-top: 20px;
    
}
.button{
    border-radius: 40px;
    padding: 10px 20px;
    gap: 5px ;
    margin: 0;
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
@media screen(min-width: 990;) {
    .font{
        font-size: small;
    }
}
</style>