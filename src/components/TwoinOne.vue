<template>
    <div class="container px-5 lg:px-20 h-[100vh] md:h-[80vh] flex flex-col-reverse md:flex-row justify-center md:justify-between items-center gap-10">
            <div class="w-full flex items-center flex-col md:items-start">
                <h1 class="text-2xl md:text-4xl text-slate-700"><strong class="text-black text-5xl lg:text-6xl font-bold font-nunito">MEME.</strong></h1>
                <h1 class="text-2xl md:text-4xl text-slate-700"><strong class="text-black text-5xl lg:text-6xl font-bold font-nunito">EARN.</strong></h1>
                <h1 class="text-2xl md:text-4xl text-slate-700"><strong class="text-black text-5xl lg:text-6xl font-bold font-nunito">SMILE.</strong></h1>
                <p class="text-lg mt-4 font-nunito text-center text-orange-500">Join Meme World</p>
                <p class="text-lg mt-4 font-nunito text-center text-black">A world of memes</p>
                <p class="text-lg mt-2 font-nunito text-center text-bl">A billion smiles</p>
                <div class="flex">
                    <img :src="imgsrc2" alt="playstorelogo" class="w-full md:w-1/2 lg:w-1/3 xl:w-1/4 mt-5">
                    <img :src="imgsrc3" alt="playstorelogo" class="w-full md:w-1/2 lg:w-1/3 xl:w-1/4 mt-5">
                </div>
            </div>
            <div class="home">
                <img :src="imgsrc1" alt="phonedesign" class="w-[80%] h-[80%] mt-5">
            </div>
    </div>
</template>

<script setup>
import { defineProps } from 'vue'
const props = defineProps(['name', 'imgsrc1','imgsrc2', 'imgsrc3', 'visit', 'btnName'])
</script>

<style  scoped>

</style>