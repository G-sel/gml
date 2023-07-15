<template>
    <link href="https://fonts.googleapis.com/css2?family=Caprasimo&family=Open+Sans:wght@500;700&display=swap" rel="stylesheet">

    <nav class="navbar navbar-light bg-warning">
  <div class="container-fluid">
    <!-- <a class="navbar-brand" href="#">Fixed bottom</a> -->
    <li class="nav">
          <a class="nav-link text-dark active" aria-current="page" href="#">Web Development</a>
        </li>
        <li class="nav">
          <a class="nav-link text-dark" href="#">UX Design</a>
        </li>
        <li class="nav">
          <a class="nav-link text-dark" href="#">UI Design</a>
        </li>
        <li class="nav">
          <a class="nav-link text-dark" href="#">Database</a>
        </li>
        <!-- <li class="nav">
          <a class="nav-link text-light" href="#"> </a>
        </li> -->
  </div>
</nav>
</template>

<script>
export default {
    name: 'FooterPage'
}
</script>

<style scoped>
.nav{
    font-family: 'Caprasimo', cursive;
}
.container-fluid{
    margin: auto 60px;
}

</style>