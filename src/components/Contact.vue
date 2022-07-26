<template>




    <div class="contact w-full flex flex-col lg:flex-row justify-center items-center pb-52">

        <div class="contact_text mx-25 lg:mx-15">
            <h5 class="text-5xl  text-black mx-10 ">Get in touch</h5>
        </div>

        <form class="w-full max-w-sm">
            <div class="flex items-center border-b border-teal-500 py-2">
                <input
                    class="appearance-none bg-transparent border-none w-full text-gray-700 mr-3 py-1 px-2 leading-tight focus:outline-none"
                    type="text" placeholder="Jane Doe" aria-label="Full name">
                <button
                    class="flex-shrink-0 bg-teal-500 hover:bg-teal-700 border-teal-500 hover:border-teal-700 text-sm border-4 text-white py-1 px-2 rounded"
                    type="button">
                    Sign Up
                </button>
                <button
                    class="flex-shrink-0 border-transparent border-4 text-teal-500 hover:text-teal-800 text-sm py-1 px-2 rounded"
                    type="button">
                    Cancel
                </button>
            </div>
        </form>

    </div>



</template>
<script>
export default {
    name: 'Contact',
}

</script>