<template>
    <template>
    <section class="pt-16 pb-7 bg-gray-900">
        <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-12 pb-12 border-b-2 border-gray-700 max-lg:gap-7">
                <div class="col-span-12 lg:col-span-7">
                    <h2 class="font-manrope font-bold text-3xl leading-tight text-white mb-2 max-lg:text-center">Sign up
                        to our Newsletter</h2>
                    <p class="text-base text-gray-400 font-normal max-lg:text-center">Stay up to date with the latest
                        update and announcement.</p>
                </div>
                <div class="col-span-12 lg:col-span-5 flex flex-col gap-4 items-center">
                    <div
                        class="flex items-center justify-between bg-gray-800 w-full max-w-md mx-auto lg:mr-0 rounded-full p-2.5 min-[470px]:p-1.5 pl-5 min-[470px]:pl-7 border border-gray-700 transition-all duration-300 hover:border-gray-400 focus-within:border-gray-400">
                        <input type="text"
                            class="bg-transparent text-base font-normal text-white placeholder:text-gray-500 focus-within:outline-0"
                            placeholder="Your email here...">
                        <button
                            class="py-3 px-7 hidden min-[470px]:block rounded-full bg-violet-500 text-base font-semibold text-white shadow-sm shadow-transparent transition-all duration-500 focus-within:outline-0 hover:bg-violet-700 focus-within:bg-violet-700 ">Submit</button>
                    </div>
                    <button
                        class="py-3 px-7 min-[470px]:hidden rounded-full bg-violet-500 text-base font-semibold text-white shadow-sm shadow-transparent transition-all duration-500 focus-within:outline-0 hover:bg-violet-700 focus-within:bg-violet-700 ">Submit</button>
                </div>
            </div>
            <div
                class="grid grid-cols-1 min-[400px]:grid-cols-2 md:grid-cols-4 gap-y-8 py-14 border-b-2 border-gray-700">
                <div class="">
                    <h6 class="text-xl font-bold text-white mb-7">Pages</h6>
                    <ul class="flex flex-col gap-6">
                        <li>
                            <NuxtLink to="/" 
                            class="text-lg font-normal text-gray-400 transition-all duration-300 hover:text-violet-400 focus-within:outline-0 focus-within:text-violet-400">
                                Home
                            </NuxtLink>
                        </li>
                        <li>
                            <NuxtLink to="/" 
                            class="text-lg font-normal text-gray-400 transition-all duration-300 hover:text-violet-400 focus-within:outline-0 focus-within:text-violet-400">
                                About
                            </NuxtLink>
                        </li>
                        <li>
                            <NuxtLink to="/" 
                            class="text-lg font-normal text-gray-400 transition-all duration-300 hover:text-violet-400 focus-within:outline-0 focus-within:text-violet-400">
                                Contact
                            </NuxtLink>
                        </li>
                        <li>
                            <NuxtLink to="/" 
                            class="text-lg font-normal text-gray-400 transition-all duration-300 hover:text-violet-400 focus-within:outline-0 focus-within:text-violet-400">
                                Services
                            </NuxtLink>
                        </li>
                    </ul>
                </div>

                <div class="">
                    <h6 class="text-xl font-bold text-white mb-7">Services & Products</h6>
                    <ul class="flex flex-col gap-6">
                        <li>
                            <NuxtLink to="/service" 
                            class="text-lg font-normal text-gray-400 transition-all duration-300 hover:text-violet-400 focus-within:outline-0 focus-within:text-violet-400">
                                UI/UX Design
                            </NuxtLink>
                        </li>
                        <li>
                            <NuxtLink to="/service" 
                            class="text-lg font-normal text-gray-400 transition-all duration-300 hover:text-violet-400 focus-within:outline-0 focus-within:text-violet-400">
                                Web Development
                            </NuxtLink>
                        </li>
                        <li>
                            <NuxtLink to="/service" 
                            class="text-lg font-normal text-gray-400 transition-all duration-300 hover:text-violet-400 focus-within:outline-0 focus-within:text-violet-400">
                                Mobile App Development
                            </NuxtLink>
                        </li>
                        <li>
                            <NuxtLink to="/service" 
                            class="text-lg font-normal text-gray-400 transition-all duration-300 hover:text-violet-400 focus-within:outline-0 focus-within:text-violet-400">
                                Consultations
                            </NuxtLink>
                        </li>
                        <li>
                            <NuxtLink to="/service" 
                            class="text-lg font-normal text-gray-400 transition-all duration-300 hover:text-violet-400 focus-within:outline-0 focus-within:text-violet-400">
                                Web/Mobile app development Training
                            </NuxtLink>
                        </li>
                    </ul>
                </div>

                <div class="">
                    <h6 class="text-xl font-bold text-white mb-7">Resources</h6>
                    <ul class="flex flex-col gap-6">
                        <li><a href="javascript:;"
                                class="text-lg font-normal text-gray-400 transition-all duration-300 hover:text-violet-400 focus-within:outline-0 focus-within:text-violet-400">FAQs</a>
                        </li>
                        <li><a href="javascript:;"
                                class="text-lg font-normal text-gray-400 transition-all duration-300 hover:text-violet-400 focus-within:outline-0 focus-within:text-violet-400">Quick
                                Start</a></li>
                    </ul>
                </div>

                <div class="">
                    <h6 class="text-xl font-bold text-white mb-7">Support</h6>
                    <ul class="flex flex-col gap-6">
                        <li><a href="javascript:;"
                                class="text-lg font-normal text-gray-400 transition-all duration-300 hover:text-violet-400 focus-within:outline-0 focus-within:text-violet-400">Customer
                                Support</a></li>
                        <li><a href="javascript:;"
                                class="text-lg font-normal text-gray-400 transition-all duration-300 hover:text-violet-400 focus-within:outline-0 focus-within:text-violet-400">Cookies</a>
                        </li>
                        <li><a href="javascript:;"
                                class="text-lg font-normal text-gray-400 transition-all duration-300 hover:text-violet-400 focus-within:outline-0 focus-within:text-violet-400">License</a>
                        </li>
                        <li><a href="javascript:;"
                                class="text-lg font-normal text-gray-400 transition-all duration-300 hover:text-violet-400 focus-within:outline-0 focus-within:text-violet-400">Terms
                                & Conditions</a></li>
                        <li><a href="javascript:;"
                                class="text-lg font-normal text-gray-400 transition-all duration-300 hover:text-violet-400 focus-within:outline-0 focus-within:text-violet-400">Privacy
                                Policy</a></li>
                    </ul>
                </div>

            </div>
            <div class="pt-7 flex flex-col min-[500px]:flex-row justify-between items-center ">
                <NuxtLink to="/" class="px-0.5 py-0.5" >
                    <img height="250" width="100" src="/public/logo.svg" alt="logo">
                </NuxtLink>
                <p class="text-base font-normal text-gray-400">©<a href="/public/logo.svg">Zipliq </a>2023, All
                    rights reserved.</p>
            </div>
        </div>
    </section>
</template>
</template>