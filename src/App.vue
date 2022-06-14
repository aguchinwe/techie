<script setup>
// import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'
import Header from './components/Header.vue'
import Home from './components/Home.vue'
import About from './components/About.vue'
import Solutions from './components/Solutions.vue'
import Products from './components/Products.vue'
import Process from './components/OurProcess.vue'
import Team from './components/Team.vue'
</script>

<template>
<div class="container">
  <!-- <header> -->
    <!-- <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" /> -->

    <!-- <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header> -->
  <Header />
  <Home />
  <About />
  <Solutions />
  <Products />
  <Process />
  <Team />
  <main>
    <!-- <TheWelcome /> -->
  </main>
  </div>
</template>

<style>
body{
    margin: 0 ;
    padding: 0;
    box-sizing: border-box;
}
h3{
  text-align: center;
}
.grid-item{
  border-radius: 5px;
    margin: 10px;
    padding: 20px;
}
.grid-item-header{
    display: flex;
    align-items: center;
    
}
/* .container{
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
    max-width: 100vw;
} */
/* @import './assets/base.css';

#app {
  max-width: 1280px;
  margin: 0 auto;
  padding: 2rem;

  font-weight: normal;
}

header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

a,
.green {
  text-decoration: none;
  color: hsla(160, 100%, 37%, 1);
  transition: 0.4s;
}

@media (hover: hover) {
  a:hover {
    background-color: hsla(160, 100%, 37%, 0.2);
  }
}

@media (min-width: 1024px) {
  body {
    display: flex;
    place-items: center;
  }

  #app {
    display: grid;
    grid-template-columns: 1fr 1fr;
    padding: 0 2rem;
  }

  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  .logo {
    margin: 0 2rem 0 0;
  }
} */
</style>
