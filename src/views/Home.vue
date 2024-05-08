<template>
    <div>
        <TwoinOne :name="'MEME'" :imgsrc1="home" :imgsrc2="google" :imgsrc3="apple" :visit="'/about'" :btnName="'Get Started'"/>
    </div>
</template>

<script setup>
import TwoinOne from '../components/TwoinOne.vue';
import home from '../assets/images/group89.png'
import google from '../assets/images/GooglePlay.png'
import apple from '../assets/images/AppStore.png'
</script>

<style scoped>

</style>