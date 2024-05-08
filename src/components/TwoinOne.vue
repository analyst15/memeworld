<template>
    <div class="container mx-auto px-5 lg:px-20 h-[100vh] md:h-[80vh] flex justify-between items-center gap-10">
            <div class="w-full flex items-center flex-col md:items-start">
                <h1 class="text-2xl md:text-4xl text-slate-700">{{ name }} <br> <strong class="text-blue-700 text-5xl lg:text-6xl font-bold">EARN.</strong></h1>
                <p class="text-2xl md:text-4xl text-slate-700">SMILE.</p>
            </div>
            <div class="home">
                <img :src="imgsrc" alt="memeimg" class="w-[80%] h-[80%] mt-5">
            </div>
    </div>
</template>

<script setup>
import { defineProps } from 'vue'
const props = defineProps(['name', 'imgsrc', 'visit', 'btnName'])
</script>

<style  scoped>

</style>