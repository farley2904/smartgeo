<template>



    <div class="min-h-screen bg-gray-100">

                        <!-- Navigation Links -->
                        <div class="hidden space-x-8 sm:-my-px sm:ml-10 sm:flex">
                            <nav-link :href="route('dashboard')" :active="route().current('dashboard')">
                                Dashboard
                            </nav-link>
                             <nav-link :href="route('page')" :active="route().current('page')">
                                Pages
                            </nav-link>
                        </div>
                    </div>


    </div>


</template>

<script>
    export default {
               props: ['href', 'active'],

        computed: {
            classes() {
                return this.active
                            ? 'inline-flex items-center px-1 pt-1 border-b-2 border-indigo-400 text-sm font-medium leading-5 text-gray-900 focus:outline-none focus:border-indigo-700 transition duration-150 ease-in-out'
                            : 'inline-flex items-center px-1 pt-1 border-b-2 border-transparent text-sm font-medium leading-5 text-gray-500 hover:text-gray-700 hover:border-gray-300 focus:outline-none focus:text-gray-700 focus:border-gray-300 transition duration-150 ease-in-out'
            }
        }
    }
</script>