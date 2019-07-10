<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <Nav/>
    <Landing />
    <About/>
    <Work/>
    <Contact/>
  </div>
</template>

<script>
import Nav from './components/Nav'
import Landing from './components/Landing'
import About from './components/About'
import Contact from './components/Contact'
import Work from './components/Work'

export default {
  name: 'app',
  components: {
    Landing,
    About,
    Nav,
    Contact,
    Work
  }
}
</script>

<style>
body {
  margin: 0;
  font-family: 'Raleway', sans-serif;
  font-weight: 400;
}
/* #app { */
  /* height: 100vh;
  width: 100vw;
  overflow: hidden;
  background-image: url('./assets/trumpet.jpg');
  background-size: cover; 
  background-attachment: fixed; */
/* } */
</style>
