<template>

<section class="hero">



    <h1 class="text-4xl">Check out our company!</h1>


    <strong>We're the best at what we do!</strong>
    <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded-full w-52 self-center" >Learn More</button>
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
    background-image: url(../assets/vue_practice_hero_background.jpg);
    background-repeat: none;
    background-position: center;
    background-size: cover;
   
    
    display: flex;
    flex-flow: column nowrap;
    justify-content: center;
    align-items: center;
    
    
}



</style>