<template>

<section class="hero text-white">



    <h1 class="text-8xl">Summit Adventure Tours</h1>


    <strong>Find your summit with adventures made to be unforgettable</strong>
    <button class="bg-orange-500 hover:bg-orange-700 text-white font-bold my-10 py-2 px-4 rounded-full w-52 self-center" >Learn More</button>
</section>

</template>


<script>

    export default {
        name: 'Hero',

    }



</script>


<style>

.hero {
    width: 100%;
    height: 100vh;
    background-image: linear-gradient(rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.5)), url(../assets/vue_practice_hero_background.jpg);
    background-repeat: none;
    background-position: center;
    background-size: cover;
   
    
    display: flex;
    flex-flow: column nowrap;
    justify-content: center;
    align-items: center;
    
    
}



</style>