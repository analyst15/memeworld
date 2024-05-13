<template>
    <div class="hidden lg:block">
        <div class="lg:ml-16 lg:pl-5 grid grid-cols-1 sm:grid-cols-2 md:grid-cols-2 lg:grid-cols-2 gap-1 p-4">
    <div class="p-4">
        <img src="../assets/images/Group89.png" alt="Description of your image" class="w-64 h-auto">
    </div>
    <div class="p-4">
        <h1 class="text-2xl md:text-4xl text-slate-700"><strong class="text-black text-5xl lg:text-6xl font-bold font-nunito">MEME.</strong></h1>
                <h1 class="text-2xl md:text-4xl text-slate-700"><strong class="text-black text-5xl lg:text-6xl font-bold font-nunito">EARN.</strong></h1>
                <h1 class="text-2xl md:text-4xl text-slate-700"><strong class="text-black text-5xl lg:text-6xl font-bold font-nunito">SMILE.</strong></h1>
                <p class="text-lg mt-4 font-nunito text-orange-500">Join Memeworld</p>
                <p class="text-lg mt-4 font-nunito text-black">A world of memes</p>
                <p class="text-lg mt-2 font-nunito text-bl">A billion smiles</p>
                <div class="flex flex-wrap">
                    <img :src="imgsrc2" alt="playstorelogo" class="w-full lg:mr-3 md:w-1/2 lg:w-1/3 xl:w-1/4 mt-5">
                    <img :src="imgsrc3" alt="appstorelogo" class="w-full md:w-1/2 lg:w-1/3 xl:w-1/4 mt-5">
                </div>
    </div>
</div>
    </div>


<div class="lg:hidden grid grid-cols-1 sm:grid-cols-2 md:grid-cols-2  gap-1 p-4">
    <div class="">
        <div class="flex text-left">
            <h1 class=""><strong class="text-black text-2xl lg:text-6xl font-bold font-nunito mr-1">MEME.</strong></h1>
            <h1 class=""><strong class="text-black text-2xl lg:text-6xl font-bold font-nunito mr-1">EARN.</strong></h1>
            <h1 class=""><strong class="text-black text-2xl lg:text-6xl font-bold font-nunito">SMILE.</strong></h1>
        </div>
        <p class="text-lg mt-4 font-nunito text-orange-500">Join Memeworld</p>
        <p class="text-lg mt-2 font-nunito text-black">A world of memes</p>
        <p class="text-lg font-nunito text-bl">A billion smiles</p>
        <div class="flex mt-3">
            <img :src="imgsrc4" alt="playstorelogo" class="w-1/3 mr-2">
            <img :src="imgsrc5" alt="appstorelogo" class="w-1/3">
        </div>
    </div>
    <div class="p-4">
        <img src="../assets/images/Group89.png" alt="Description of your image" class="w-64 h-auto mx-auto">
    </div>
</div>



 <!----<div class=" grid grid-cols-1 sm:grid-cols-2 md:grid-cols-2 lg:grid-cols-2 gap-4 p-4">
    <div class="p-4">
        <div class="mr-10">
                <img :src="imgsrc1" alt="phonedesign" class="w-[80%] h-[80%] lg:px-24">
            </div>
    </div>
    <div class="p-4">
        <div class="w-full flex items-center flex-col md:items-start">
                <h1 class="text-2xl md:text-4xl text-slate-700"><strong class="text-black text-5xl lg:text-6xl font-bold font-nunito">MEME.</strong></h1>
                <h1 class="text-2xl md:text-4xl text-slate-700"><strong class="text-black text-5xl lg:text-6xl font-bold font-nunito">EARN.</strong></h1>
                <h1 class="text-2xl md:text-4xl text-slate-700"><strong class="text-black text-5xl lg:text-6xl font-bold font-nunito">SMILE.</strong></h1>
                <p class="text-lg mt-4 font-nunito text-center text-orange-500">Join Meme World</p>
                <p class="text-lg mt-4 font-nunito text-center text-black">A world of memes</p>
                <p class="text-lg mt-2 font-nunito text-center text-bl">A billion smiles</p>
                <div class="flex">
                    <img :src="imgsrc2" alt="playstorelogo" class="w-full md:w-1/2 lg:w-1/3 xl:w-1/4 mt-5">
                    <img :src="imgsrc3" alt="appstorelogo" class="w-full md:w-1/2 lg:w-1/3 xl:w-1/4 mt-5">
                </div>
            </div>
    </div>
   </div>-->
   

<!----</div>
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
                    <img :src="imgsrc3" alt="appstorelogo" class="w-full md:w-1/2 lg:w-1/3 xl:w-1/4 mt-5">
                </div>
            </div>
            <div class="home">
                <img :src="imgsrc1" alt="phonedesign" class="w-[80%] h-[80%] mt-5">
            </div>
    </div>-->
</template>

<script setup>
import { defineProps } from 'vue'
const props = defineProps(['name', 'imgsrc1','imgsrc2', 'imgsrc3','imgsrc4', 'imgsrc5', 'visit', 'btnName'])
</script>

<style  scoped>

</style>