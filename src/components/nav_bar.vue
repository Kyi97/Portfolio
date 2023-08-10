<script setup>

</script>

<template>
    <nav class=" border-gray-200 bg-[#d5e4c3] ">
        <div class="flex flex-wrap items-center justify-between mx-auto p-4 ml-16 mr-16 h-24">
            <a href="#" class="flex items-center">
                <!-- <img src="https://i.pinimg.com/280x280_RS/16/04/1b/16041ba2d0b2f58a9f14fbe361428201.jpg" class="h-8 mr-3"
                    alt="kyi Logo" /> -->
            </a>
            <button data-collapse-toggle="navbar-hamburger" type="button"
                class="inline-flex items-center justify-center p-2 w-10 h-10 ml-3 text-sm text-[#c54b6c] rounded-lg "
                aria-controls="navbar-hamburger" aria-expanded="false">
                <span class="sr-only">Open main menu</span>
                <svg class="w-16 h-16" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none"
                    viewBox="0 0 17 14">
                    <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                        d="M1 1h15M1 7h15M1 13h15" />
                </svg>
            </button>
            <div class="hidden w-full" id="navbar-hamburger">
                <ul class="flex flex-col font-medium mt-4 rounded-lg bg-gray-50 dark:bg-gray-800 dark:border-gray-700">
                    <li>
                        <a href="#" class="block py-2 pl-3 pr-4 text-white bg-blue-700 rounded dark:bg-blue-600"
                            aria-current="page">Home</a>
                    </li>
                    <li>
                        <a href="#"
                            class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white">Services</a>
                    </li>
                    <li>
                        <a href="#"
                            class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white">Pricing</a>
                    </li>
                    <li>
                        <a href="#"
                            class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>

<style scoped></style>
