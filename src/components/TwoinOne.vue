<template>
    <div class="container mx-auto px-5 lg:px-20">
        <div class="flex justify-between gap-10">
            <div class="text">
                <h1 class="text-2xl md:text-4xl text-slate-700">{{ name }} <br> <strong class="text-blue-700 text-5xl lg:text-6xl font-bold">MemeWorld Team</strong></h1>
            </div>
            <div class="img"></div>
        </div>
    </div>
</template>

<script setup>
import { defineProps } from 'vue'
const props = defineProps(['name', 'imgsrc', 'visit', 'btnName'])
</script>

<style  scoped>

</style>