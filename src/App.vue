<template>
  <link href="https://fonts.googleapis.com/css2?family=Caprasimo&family=Open+Sans:wght@500;700&display=swap" rel="stylesheet">
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <landingPage/>
  <SkillPage/>
  <!-- <FooterPage/> -->
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import landingPage from './components/landingPage.vue'
import SkillPage from './components/SkillPage.vue';
// import FooterPage from './components/FooterPage.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    landingPage,
    SkillPage
    // FooterPage
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
</style>
