<template>




    <div class="banner  flex items-center justify-center h-screen m-auto mb-12 bg-fixed bg-center bg-cover custom-img w-full">



        <div class="p-5 text-2xl text-white bg-purple-300 bg-opacity-50 rounded-xl flex flex-col">

            <strong class="text-6xl">Get in Touch</strong>
            <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 border border-blue-700 rounded">
                Contact
            </button>




        </div>


    </div>


</template>

<script>

export default {
    name: 'Banner'
}


</script>


<style>
.banner {
    width: 100%;
    background-image: url(../assets/pexels-eberhard-grossgasteiger-673020.jpg);
    height: 35vh;
    background-position: center;
    background-size: cover;

}
</style>