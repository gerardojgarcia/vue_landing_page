

<template>
<div >
  
    <Header/>
    <Hero/>
    <About />
    <Banner/>
    <Team />
</div>
</template>

<script >
import Header from './components/Header.vue'
import Hero from './components/Hero.vue'
import About from './components/About.vue'
import Banner from './components/Banner.vue'
import Team from './components/Team.vue'

export default {
  name: 'App',
  components: {
    Header,
    Hero,
    About,
    Banner,
    Team
    
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


