

<template>
<div >
  
    <Header/>
    <Hero/>
    <About />
    <Banner/>
    <Team />
    <Contact/>  
  
</div>
</template>

<script >
import Header from './components/Header.vue'
import Hero from './components/Hero.vue'
import About from './components/About.vue'
import Banner from './components/Banner.vue'
import Team from './components/Team.vue'
import Signup from './components/Signup.vue'
import Contact from './components/Contact.vue'

export default {
  name: 'App',
  components: {
    Header,
    Hero,
    About,
    Banner,
    Team,
    Signup,
    Contact
}
}

</script>
<style scoped>


  .container {
    width: 100%;
    
    display: flex;
    flex-flow: column nowrap;


  }



</style>


