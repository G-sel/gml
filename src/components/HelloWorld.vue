<template>
<!-- new nav bar -->
<nav class="navbar navbar-expand-lg bg-dark">
  <div class="container-fluid">
    <a class="navbar-brand logo text-warning" href="#">GL.</a>
    <!-- <a class="navbar-brand" href="#">Navbar w/ text</a> -->
    <button class="navbar-toggler navbar-light-active-color" type="button" data-bs-toggle="collapse" data-bs-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon "></span>
    </button>
    <div class="collapse navbar-collapse " id="navbarText">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a href="#" class="nav-link navText" >Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link navText " href="#">About Me</a>
        </li>
        <li class="nav-item">
          <a class="nav-link navText " href="https://www.facebook.com/gseeeel">Contact</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Kanit:ital,wght@0,300;0,400;1,300;1,400&display=swap');

template{
  font-family: 'Kanit', sans-serif;
}
svg{
  fill: #FFC930;
  margin: auto 10px;
  /* margin-top: 10px; */
  height: 20px;
  width: 20px;
}
svg:hover{
  transform: scale(2);
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.logo{
  font-family: 'Caprasimo', cursive;
  font-size: x-large;
}
.container-fluid{
  display: flex;
  justify-content: space-between;
  align-content: space-between;
  margin: auto 60px;
}

.navText{
  color: #fff;
  font-family: 'Kanit', sans-serif;
  scroll-behavior: smooth;
}
.navText:hover{
  color: #FFC930;
}

.burger[aria-expanded="true"] {
  outline: 1px solid #FFC930;
  background-color: #212529;
  color: #FFC930 !important;
}

.burger:hover{
  outline: 2px solid #212529;
  background-color: #FFC930;
}
</style>
