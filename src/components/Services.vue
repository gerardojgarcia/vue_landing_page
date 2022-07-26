<template>


    <section class="services mb-36 text-black">

        <div class="service_container flex flex-col justify-center items-center ">


            <div class="service_text">

</div>

                <h3 class="text-6xl my-7 text-black w-full">Pick an Adventure </h3>


                <div class="service_cards flex-col lg:flex-row justify-center items-center ">


                    <div class="max-w-sm rounded overflow-hidden shadow-lg bg-white text-black">
                        <img class="w-full" src="../assets/pexels-lumn-167684.jpg" alt="Sunset in the mountains">
                        <div class="px-6 py-4">
                            <div class="font-bold text-xl mb-2">The Coldest Sunset</div>
                            <p class="text-gray-700 text-base">
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus quia, nulla!
                                Maiores et perferendis eaque, exercitationem praesentium nihil.
                            </p>
                        </div>
                        <div class="px-6 pt-4 pb-2 ">
                            <span
                                class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#photography</span>
                            <span
                                class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#travel</span>
                            <span
                                class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#winter</span>
                        </div>
                        <button class="bg-orange-500 hover:bg-orange-700 text-white font-bold py-2 px-4 border  rounded my-6">
  Book Now
</button>
                    </div>

                    <div class="max-w-sm rounded overflow-hidden shadow-lg bg-white">
                        <img class="w-full" src="../assets/pexels-stephan-seeber-1054218.jpg" alt="Sunset in the mountains">
                        <div class="px-6 py-4 ">
                            <div class="font-bold text-xl mb-2">Sierra's First Frost</div>
                            <p class="text-gray-700 text-base">
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus quia, nulla!
                                Maiores et perferendis eaque, exercitationem praesentium nihil.
                            </p>
                        </div>
                        <div class="px-6 pt-4 pb-2">
                            <span
                                class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#photography</span>
                            <span
                                class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#travel</span>
                            <span
                                class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#winter</span>
                        </div>
                        <button class="bg-orange-500 hover:bg-orange-700 text-white font-bold py-2 px-4 border  rounded my-6">
  Book Now
</button>
                    </div>
                    <div class="max-w-sm rounded overflow-hidden shadow-lg bg-white">
                        <img class="w-full" src="../assets/pexels-tyler-lastovich-633198.jpg" alt="Sunset in the mountains">
                        <div class="px-6 py-4">
                            <div class="font-bold text-xl mb-2">The Resting Giant</div>
                            <p class="text-gray-700 text-base">
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus quia, nulla!
                                Maiores et perferendis eaque, exercitationem praesentium nihil.
                            </p>
                        </div>
                        <div class="px-6 pt-4 pb-2">
                            <span
                                class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#photography</span>
                            <span
                                class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#travel</span>
                            <span
                                class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">#winter</span>
                        </div>

                        <button class="bg-orange-500 hover:bg-orange-700 text-white font-bold py-2 px-4 border  rounded my-6">
  Book Now
</button>
                    </div>


                    
                </div>
            


        </div>


    </section>


</template>

<script>

export default {
    name: 'Services',

}



</script>


<style>

.service_container {
    width: 100%; 
    justify-content: center;
    align-items: center; 
}
.service_cards {

    width: 100%;
    display: flex;


}

.service_cards>div {
    margin: 15px;
}
</style>