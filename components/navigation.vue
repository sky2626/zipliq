<template>

    <Head>
        <link rel="preconnect" href="https://fonts.googleapis.com" />
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
        <link
            href="https://fonts.googleapis.com/css2?family=Alkatra:wght@400..700&family=Dosis:wght@200..800&family=Pacifico&family=Space+Grotesk:wght@300..700&display=swap"
            rel="stylesheet" />
    </Head>
    <nav class="">
        <!-- Desktop navigation -->
        <div class="md:flex md:justify-center md:items-center pacifico-font hidden">
            <div
                class=" flex items-center justify-between w-full max-w-[1200px] bg-white py-4 px-8 rounded-full shadow-lg shadow-[#471D79]/25">
                <ul class="flex gap-4">
                    <li>
                        <NuxtLink to="/"
                            class="block text-lg  text-[#471D79] transition-all duration-300 hover:text-violet-400 focus-within:outline-0 focus-within:text-violet-400">
                            Home
                        </NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/about"
                            class="block text-lg text-[#471D79] transition-all duration-300 hover:text-violet-400 focus-within:outline-0 focus-within:text-violet-400">
                            About
                        </NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/service"
                            class="block text-lg text-[#471D79] transition-all duration-300 hover:text-violet-400 focus-within:outline-0 focus-within:text-violet-400">
                            Services
                        </NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/contact"
                            class="block text-lg text-[#471D79] transition-all duration-300 hover:text-violet-400 focus-within:outline-0 focus-within:text-violet-400">
                            Cantact
                        </NuxtLink>
                    </li>
                </ul>
                <img src="/public/logo.svg" width="100" height="80" alt="logo" class="">
                <NuxtLink to="/service" class="flex gap-4 items-center justify-center hover:gap-6 ">
                    <h1 class="text-[#471D79] text-lg ">Free Quote</h1>
                    <IconsArrow class="text-[#471D79]" />
                </NuxtLink>
            </div>

        </div>

        <!-- Mobile menu navigation -->
        <div
            class="bg-white text-[#471D79] p-4 flex items-center justify-between md:hidden rounded-full shadow-lg shadow-[#471D79]/25">
            <img src="/public/logoonly.svg" width="50" height="40" alt="logo" class="">
            <button @click="toggleMenu" class="block md:hidden text-white focus:outline-none">
                <IconsMenu v-if="!menuOpen" class="text-[#471D79] font-bold text-2xl" />
                <IconsClose v-else class="text-[#471D79] font-bold text-xl" />
            </button>
        </div>
        <div :class="menuOpen ? 'max-h-60' : 'max-h-0'"
            class="w-full md:flex md:items-center md:w-auto overflow-hidden transition-max-height duration-300 ease-in-out">
            <ul class="flex md:hidden flex-col ml-8 mt-4 space-y-4 pacifico-font">
                <li>
                    <NuxtLink to="/"
                        class="block text-lg text-[#471D79] transition-all duration-300 hover:text-violet-400 focus-within:outline-0 focus-within:text-violet-400">
                        Home
                    </NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/about"
                        class="block text-lg text-[#471D79] transition-all duration-300 hover:text-violet-400 focus-within:outline-0 focus-within:text-violet-400">
                        About
                    </NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/service"
                        class="block text-lg text-[#471D79] transition-all duration-300 hover:text-violet-400 focus-within:outline-0 focus-within:text-violet-400">
                        Services
                    </NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/contact"
                        class="block text-lg text-[#471D79] transition-all duration-300 hover:text-violet-400 focus-within:outline-0 focus-within:text-violet-400">
                        Cantact
                    </NuxtLink>
                </li>
            </ul>
        </div>
    </nav>
</template>

<script setup>
import { ref } from 'vue';

// State for menu toggle
const menuOpen = ref(false);
const toggleMenu = () => {
    menuOpen.value = !menuOpen.value;
};
</script>

<style scoped>
/* Transition for height when opening and closing the mobile menu */
.transition-max-height {
    transition: max-height 0.3s ease-in-out;
}

.pacifico-font {
    font-family: 'Pacifico', cursive;
}

.alkatra-font {
    font-family: 'Alkatra', sans-serif;
}

.dosis-font {
    font-family: 'Dosis', sans-serif;
}

.space-grotesk-font {
    font-family: 'Space Grotesk', sans-serif;
}
</style>