

<template>
<div >
  
    <Header/>
    <Hero/>
    <About />
    <Banner/>
</div>
</template>

<script >
import Header from './components/Header.vue'
import Hero from './components/Hero.vue'
import About from './components/About.vue'
import Banner from './components/Banner.vue'

export default {
  name: 'App',
  components: {
    Header,
    Hero,
    About,
    Banner
    
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


