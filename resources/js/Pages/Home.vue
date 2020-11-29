<template>
<div>
    <header class="bg-white">
        <div class="max-w-7xl mx-auto px-2 sm:px-6 lg:px-8">
            <div class="relative flex items-center justify-between h-16">
                <div class="flex-1 flex items-center justify-center sm:items-stretch sm:justify-start">
                    <div class="flex-shrink-0 flex items-center">
                        <img class="block lg:hidden h-8 w-auto" src="images/logo-mini.svg" alt="Smartgeo">
                        <jet-application-logo class="hidden lg:block h-8 w-auto" />
                    </div>
                </div>
                <div class="flex-1 flex items-center justify-center sm:items-stretch sm:justify-start">
                    <div class="flex-shrink-0 flex items-center">
                       Сайт в разработке. Зайдите позже.
                    </div>
                </div>
                <div class="absolute inset-y-0 right-0 flex items-center pr-2 sm:static sm:inset-auto sm:ml-6 sm:pr-0">
                    +38 (050) 086 60 09
                </div>
            </div>
        </div>
    </header>
    <main>
        <div class="max-w-7xl mx-auto py-6 sm:px-6 lg:px-8">
            <h1 class="text-6xl font-bold leading-tight text-white">Геодезия и 3Д<br>сканирование</h1>
            <h2 class="text-2xl text-white">професионализм и качество в сфере геодезических услуг</h2>
            <nav class="">
                <ul class="flex mt-40">
                    <li class="mx-1"><a href="#1"><img src="images/1.jpg" alt="1"></a></li>
                    <li class="mx-1"><a href="#2"><img src="images/2.jpg" alt="2"></a></li>
                    <li class="mx-1"><a href="#3"><img src="images/3.jpg" alt="3"></a></li>
                    <li class="mx-1"><a href="#4"><img src="images/4.jpg" alt="4"></a></li>
                </ul>
            </nav>
        </div>
    </main>
</div>
</template>

<script>
    import JetApplicationLogo from '@/Jetstream/ApplicationLogo'

    export default {
        components: {
            JetApplicationLogo,
        },
    }
</script>

