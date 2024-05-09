<template>
    <div>
        <header class="flex justify-between items-center bg-orange-500 shadow-md h-[80px] px-5 lg:px-24 relative z-10">
            <div class="text-3xl font-extrabold text-blue-600 hover:text-blue-700 cursor-pointer">
                <router-link to="/"><i class="bi bi-code"></i>Memeworld</router-link>
            </div>
            <nav class="flex flex-col md:flex-row p-5 gap-4 md:gap-10 px-6 md:static absolute bg-orange-500 md:bg-transparent shadow-md md:shadow-none md:w-auto my-7 md:my-0 left-0 w-full duration-500" :class="[open ? 'top-0' : 'top-[-390%]']">
                <router-link to="/" class="text-white py-5 hover:text-slate-700 text-base font-normal">Blog</router-link>
                <router-link to="/about" class="text-white py-5 hover:text-slate-700 text-base font-normal">Features</router-link>
                <router-link to="/services" class="text-white py-5 hover:text-slate-700 text-base font-normal">Contact Us</router-link>
            </nav>
            <div class="test-4xl text-black cursor-pointer md:hidden z-20" @click="menuOpen">
                <i :class="[open ? 'text-3xl bi bi-x' : ' text-3xl bi bi-list' ]"></i>
            </div>
        </header>
    </div>
</template>

<script setup>

import { RouterLink } from 'vue-router'
import { ref } from 'vue';

const open = ref(false)

const menuOpen = () => {
    open.value = !open.value
}

</script>

<style scoped>

</style>