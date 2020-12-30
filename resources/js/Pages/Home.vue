<template>
<div>
    <header class="bg-white">
        <div class="max-w-7xl mx-auto px-2 sm:px-6 lg:pl-40 lg:pr-28">
            <div class="relative flex items-center justify-between h-16">
                <div class="flex-1 flex items-center justify-center sm:items-stretch sm:justify-start">
                    <div class="flex-shrink-0 flex items-center">
                        <a href="/">
                            <img class="block lg:hidden h-8 w-auto" src="images/logo-mini.svg" alt="Smartgeo">
                            <jet-application-logo class="hidden lg:block h-8 w-auto" />
                        </a>
                    </div>
                </div>
                <div class="flex-1 flex items-center justify-center sm:items-stretch sm:justify-start">
                    <div class="flex-shrink-0 flex items-center">
                    	+38 (050) 086 60 09
                    </div>
                </div>
                <div class="absolute inset-y-0 right-0 flex items-center pr-2 sm:static sm:inset-auto sm:ml-6 sm:pr-6">
                      <a href="#o_nas">О нас</a>
                </div>
            </div>
        </div>
    </header>
    <main class="">
    	<section class="flex flew-wrap">
	        <div class="w-3/4 text-white max-w-7xl mx-auto pt-10 pl-40">
	            <h1 class="text-5xl font-medium leading-none">Геодезия и 3D<br>сканирование</h1>
	            <h2 class="text-xl">профессионализм и качество в сфере геодезических услуг</h2>
	        </div>
	        <div class="w-1/4">
	            <a href="#gmail" class="rounded-full block mt-10">
	                <img class="mx-auto" src="images/gmail.svg" alt="Gmail">
	            </a>
	            <a href="#telegram" class="rounded-full block my-3">
	                <img class="mx-auto" src="images/telegram.svg" alt="Telegeam">
	            </a>
	            <a href="https://www.facebook.com/smart.geo.92" class="rounded-full block">
	                <img class="mx-auto" src="images/facebook.svg" alt="Facebook">
	            </a>     
	        </div>
    	</section>
		<nav class="text-white pl-40 pr-32">
		    <ul class="flex mt-40">
		        <li class="mx-1 ">
		            <a href="#3d_skanirovanie">
		                <p class="bg-black relative top-6 z-10 text-center">3D сканирование</p>
		                <img class="relative z-0 h-48 w-full object-cover" src="images/1.jpg" alt="1">
		            </a>
		        </li>
		        <li class="mx-1">
		            <a href="#fasady">
		                <p class="bg-black relative top-6 z-10 text-center">фасады</p>
		                <img class="relative z-0 h-48 w-60 object-right object-cover" src="images/2.jpg" alt="1">
		            </a>
		        </li>
		        <li class="mx-1">
		            <a href="#v_stroitelstve">
		                <p class="bg-black relative top-6 z-10 text-center">в строительстве</p>
		                <img class="relative z-0 h-48 w-60 object-right object-cover" src="images/3.jpg" alt="1">
		            </a>
		        </li>
		        <li class="mx-1">
		            <a href="#izyskaniya">
		                <p class="bg-black relative top-6 z-10 text-center">изыскания</p>
		                <img class="relative z-0 h-48 w-60 object-right object-cover" src="images/4.jpg" alt="1">
		            </a>
		        </li>
		    </ul>
		</nav>
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

