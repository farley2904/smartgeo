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
                <div class="absolute inset-y-0 right-0 flex items-center pr-2 sm:static sm:inset-auto sm:ml-6 sm:pr-0">
                    <button class="rounded-full text-gray-400 hover:text-white focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-offset-gray-800 focus:ring-white">
                        <span class="sr-only">Facebook</span>
                        <!-- Heroicon name: bell -->
                        <svg width="21" height="21" viewBox="0 0 21 21" fill="none" xmlns="http://www.w3.org/2000/svg" stroke="currentColor" aria-hidden="true">
                        <path d="M20.8804 10.7476C20.8804 5.18158 16.3631 0.664246 10.7971 0.664246C5.23108 0.664246 0.713745 5.18158 0.713745 10.7476C0.713745 15.6279 4.18241 19.6915 8.78042 20.6293V13.7726H6.76375V10.7476H8.78042V8.22675C8.78042 6.28067 10.3635 4.69758 12.3096 4.69758H14.8304V7.72258H12.8138C12.2592 7.72258 11.8054 8.17633 11.8054 8.73092V10.7476H14.8304V13.7726H11.8054V20.7805C16.8975 20.2763 20.8804 15.9808 20.8804 10.7476Z" fill="#232426"/>
                        </svg>
                    </button>
                     <button class="mx-3 rounded-full text-gray-400 hover:text-white focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-offset-gray-800 focus:ring-white">
                        <span class="sr-only">Gmail</span>
                        <!-- Heroicon name: bell -->
                        <svg width="22" height="18" viewBox="0 0 22 18" fill="none" xmlns="http://www.w3.org/2000/svg" stroke="currentColor" aria-hidden="true">
                            <path d="M19.6602 15.6526H17.5323V6.3431L11.1486 10.3329L4.76494 6.3431V15.6526H2.63705V2.88528H3.91378L11.1486 7.40704L18.3834 2.88528H19.6602V15.6526ZM19.6602 0.757385H2.63705C1.45607 0.757385 0.509155 1.7043 0.509155 2.88528V15.6526C0.509155 16.217 0.733343 16.7582 1.1324 17.1573C1.53146 17.5563 2.07269 17.7805 2.63705 17.7805H19.6602C20.2245 17.7805 20.7658 17.5563 21.1648 17.1573C21.5639 16.7582 21.7881 16.217 21.7881 15.6526V2.88528C21.7881 2.32092 21.5639 1.77969 21.1648 1.38063C20.7658 0.981573 20.2245 0.757385 19.6602 0.757385Z" fill="#232426"/>
                        </svg>
                    </button>
                     <button class="rounded-full text-gray-400 hover:text-white focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-offset-gray-800 focus:ring-white">
                        <span class="sr-only">Telegeam</span>
                        <!-- Heroicon name: bell -->
                        <svg width="21" height="20" viewBox="0 0 21 20" fill="none" xmlns="http://www.w3.org/2000/svg" stroke="currentColor" aria-hidden="true">
                            <path d="M10.7509 0.210815C5.30432 0.210815 0.889038 4.6261 0.889038 10.0727C0.889038 15.5193 5.30432 19.9346 10.7509 19.9346C16.1976 19.9346 20.6129 15.5193 20.6129 10.0727C20.6129 4.6261 16.1976 0.210815 10.7509 0.210815Z" fill="#232426"/>
                            <path d="M15.5497 5.88375L13.7882 14.7648C13.7882 14.7648 13.5419 15.3807 12.8644 15.0851L8.79958 11.9687L7.32152 11.2543L4.83338 10.4167C4.83338 10.4167 4.45154 10.2812 4.41456 9.98561C4.37757 9.68999 4.84571 9.52988 4.84571 9.52988L14.7366 5.64984C14.7366 5.64984 15.5496 5.29265 15.5496 5.88391" fill="white"/>
                            <path d="M8.48712 14.6649C8.48712 14.6649 8.36847 14.6538 8.22054 14.1857C8.07284 13.7176 7.32141 11.2541 7.32141 11.2541L13.2954 7.46038C13.2954 7.46038 13.6404 7.25097 13.628 7.46038C13.628 7.46038 13.6896 7.49736 13.5048 7.66979C13.3201 7.8423 8.81187 11.8947 8.81187 11.8947" fill="#D2E5F1"/>
                            <path d="M10.3581 13.1634L8.75037 14.6293C8.75037 14.6293 8.62463 14.7247 8.48718 14.6649L8.79506 11.9421" fill="#B5CFE4"/>
                        </svg>
                    </button>
                </div>
            </div>
        </div>
    </header>
    <main>
    <div class="max-w-7xl mx-auto py-6 sm:px-6 lg:px-8">
      <!-- Replace with your content -->
      <div class="px-4 py-6 sm:px-0">
        <h1 class="text-3xl font-bold leading-tight text-white">
        Геодезия сканирование
      </h1>
      <h2 class="text-white">професионализм и качество в сфере геодезических услуг
      </h2>
        <div class="border-4 border-dashed border-gray-200 rounded-lg h-96"></div>
      </div>
      <!-- /End replace -->
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

