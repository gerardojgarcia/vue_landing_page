<template>

    <header>

        <nav class="flex items-center justify-between flex-wrap bg-black p-6 w-full">
            <div class="flex items-center flex-shrink-0 text-white mr-6">
                
                <span class="font-semibold text-xl text-orange-200 tracking-tight">SummitAdventures</span>
            </div>
            <div class="block lg:hidden">
                <button
                    class="flex items-center px-3 py-2 border rounded text-teal-200 border-teal-400 hover:text-white hover:border-white">
                    <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                        <title>Menu</title>
                        <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z" />
                    </svg>
                </button>
            </div>
            <div class="w-full block flex-grow lg:flex lg:items-center lg:w-auto">
                <div class="text-sm lg:flex-grow">
                    <a href="#responsive-header"
                        class="block mt-4 lg:inline-block lg:mt-0 text-orange-200 hover:text-white mr-4">
                        Home
                    </a>
                    <a href="#responsive-header"
                        class="block mt-4 lg:inline-block lg:mt-0 text-orange-200 hover:text-white mr-4">
                        About
                    </a>
                    <a href="#responsive-header"
                        class="block mt-4 lg:inline-block lg:mt-0 text-orange-200 hover:text-white">
                        Services
                    </a>
                </div>
                <div>
                    <a href="#"
                        class="inline-block text-sm px-4 py-2 leading-none border rounded text-white border-white hover:border-transparent hover:text-orange-500 hover:bg-white mt-4 lg:mt-0">Contact</a>
                </div>
            </div>
        </nav>
    </header>


</template>

<script>

export default {
    name: 'Header',

    data() {
        return {
            links: [
                {
                    id: 1,
                    link: 'Home',
                    href: 'http://home.net'
                },
                {
                    id: 2,
                    link: 'Services',
                    href: 'http://home.net'
                },

            ]


        }
    }
}


</script>



<style>
header {
    width: 100%;

    display: flex;
    justify-content: space-between;
}
</style>